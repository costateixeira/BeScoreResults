# TODO — common-translations CodeSystem / ValueSet / Questionnaire generation

`generate_codesystems.py` currently emits, per recognised "head" key:
1. `CS_<head>` — CodeSystem with all matching child concepts
2. `VS_<head>` — ValueSet including all codes from the CodeSystem
3. `Q_<head>` — Questionnaire with one `choice` item, contained inline ValueSet

After filtering `my_*` keys (696 dropped), the run produces **98** of each, plus
one `CS_CommonTranslationsOther` catch-all (28 leftover concepts, no VS/Q).

The cases below are deliberately deferred — they need
product/terminology decisions before code can land.

## 1. Orphan groups (children exist but no top-level head)

These need a synthesized head with a chosen title before they can be emitted
as standalone CodeSystems.

| prefix | children | notes |
|---|---|---|
| `scr_02` | 7 ranges (`scr_02_range_0_0.49` … `scr_02_range_5.50_6`) | decimal cut-points |
| `scr_03` | 7 values (`scr_03_0` … `scr_03_6`) | 4-ADL severity |
| `scr_04` | 7 values | |
| `scr_05` | 5 values with **decimal codes** (`0`, `1.5`, `3`, `4.5`, `6`) | weighted screener, 1.5 pts/problem |
| `scr_06` | 7 values | behavioural-problem severity |
| `scr_BIS_EPA` | 3 values (+ `_NA`, `_NO` not yet routed) | |
| `scr_BIS_PICT1` | 4 values (+ `_NA`, `_NO`) | |
| `scr_BIS_pallzorg` | 5 values | |
| `section` | 5 values (`section_02` … `section_06`) | |
| `aSRI` | 2 values (`aSRI_0`, `aSRI_1`) | |

**Open question**: are these one big `CS_Screeners` or many small ones?
Top-level keys `screeners`, `scales`, `bisEPA`, `bisPict1`, `bisPallzorg`
look like category headers that suggest the latter — but they would need
titles supplied since the children carry no head translation.

## 2. Score-scale heads with only `_unique` (no enumerated concepts)

These describe **continuous numeric scores**, not enumerable answer sets.
Best modelled as a Quantity range, not as a CodeSystem. Currently skipped.

`sADLLF`, `sADLSF`, `sDIVERT`, `sDSI`, `sFUNH`, `sHSADLSF`, `sHSDRSSF`,
`sMANIA`, `sPSSL`, `sPSSS`, `sRHO`, `sRISE`, `sSCI`, `sSOCWD`, `sSOS`

Decision needed:
- (a) Skip entirely (current behaviour). They live only as documentation
  inside `_unique` translations.
- (b) Emit a stub CodeSystem with no concepts and the `_unique` text as
  Description, so they appear in the IG artifact list.
- (c) Emit them as `Questionnaire` items of type `decimal`/`integer` with
  the `_unique` text as the question hint, no answer set.

(c) is the most clinically faithful — the question becomes "enter a score
0–15" rather than picking from a list.

## 3. Free-form / inconsistent range encodings

These don't match `_interval_a_b` or `_range_a_b` cleanly and currently
fall into the orphan list (item 1):

- `sPURS_1_2`, `sPURS_4_5`, `sPURS_6_7_8` — bare multi-numeric ranges,
  no `_range_` infix. Mis-parsed as orphan prefixes `sPURS_1`, `sPURS_4`,
  `sPURS_6_7`.
- `sFRAILTY_range_0_1_0_9` — looks like `0.1` to `0.9` with the dot stripped
  to underscore. Currently mis-parsed as orphan prefix `sFRAILTY_range_0_1`.
  Either fix the source data (use `0.1`/`0.9`) or special-case parsing.
- `sBMI_interval_0_18.5` — the dot survives correctly here, the regex
  handles it. No action unless source data is normalised.

## 4. Special-status concepts inside screener families

- `scr_BIS_EPA_NA`, `scr_BIS_EPA_NO`, `scr_BIS_PICT1_NA`, `scr_BIS_PICT1_NO`
  — "not applicable" / "not observed". When the parent `scr_BIS_*` group
  is synthesized (item 1), decide whether they belong as concepts there
  or in a shared status CodeSystem.

## 5. Implicit groupings in extras

The 28 top-level keys with no children currently land in
`CS_CommonTranslationsOther`. Some look like coherent sets that probably
want their own CodeSystem:

- `cap_domain_safety`, `cap_domain_autonomy`,
  `cap_domain_functional_performance`, … (5 keys) → likely `CS_CAPDomain`
- `bisEPA`, `bisPict1`, `bisPallzorg` → category labels for `scr_BIS_*`
  families
- `screeners`, `scales`, `caps`, `main`, `99999` → mixed metadata;
  case-by-case

## 6. Canonical URLs

Currently no `^url` is set. SUSHI defaults `^url` to
`<canonical>/CodeSystem/<id>`, i.e.
`https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/<id>`.

If a different prefix is required (e.g. shared `terminology` namespace
as in be-medication:
`https://www.ehealth.fgov.be/standards/fhir/terminology/CodeSystem/<id>`),
add `* ^url = "..."` in `emit_codesystem`.

## 7. Decimal-code screeners

`scr_05_*` uses scores `0, 1.5, 3, 4.5, 6` (each problem worth 1.5
points, top bin folds 4–5 problems). FHIR codes accept dots, but verify
that `* #scr_05_1.5 "..."` round-trips through SUSHI and the publisher
when this group is emitted (item 1).

## 8. Catch-all CodeSystem has no VS/Q

`CS_CommonTranslationsOther` exists as a CodeSystem only — no ValueSet
or Questionnaire is generated for it. If those leftover concepts need
to be presentable in the questionnaire-preview workflow, regroup them
(item 5) so each coherent subset gets its own CS+VS+Q triple.

## 9. Data-quality outliers

- `sDSI_XWESP_unique` — single occurrence with malformed prefix.
  Currently routes its description to a non-existent prefix
  `sDSI_XWESP` and is silently lost.
- `99999` as a numeric pseudo-code at top level — emitted into the
  catch-all CS as concept code `99999`. Numeric codes are legal in
  FHIR but worth flagging.

## 10. Questionnaire item type

Today every generated Questionnaire has a single `choice` item. For
concepts that are **ranges or intervals** (`sBMI`, `sCAGE`, the `*_range_*`
families), `choice` may not be the right item type — the user is supposed
to enter a number that maps into a range, not pick a range as an answer.
Possible fix: detect whether a head's children are ranges/intervals and
emit `decimal` or `integer` item type with `enableWhen` mapping rules,
or split the questionnaire into a number-entry + computed-band pattern.

## Suggested order

1. Land mechanical fixes (`my_*` filter, decimal `_N`, `_interval_`,
   `_range_`, `_unique`-as-description, CS+VS+Q triples) — **done**.
2. Decide canonical URL prefix (item 6).
3. Decide questionnaire item type for range-only heads (item 10).
4. Decide orphan-head naming/titling → emit synthesized heads (item 1).
5. Decide Quantity-vs-CodeSystem for the 15 `_unique`-only scales (item 2).
6. Group `cap_domain_*` and `bis*` into their own CodeSystems (item 5).
7. Resolve free-form ranges (item 3): data fix or special-case parser.
