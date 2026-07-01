# Vrijheidsbeperkende maatregelen - v0.1.0

## CodeSystem: Vrijheidsbeperkende maatregelen 

 
Vrijheidsbeperkende maatregelen 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhctrlint",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhctrlint",
  "version" : "0.1.0",
  "name" : "CS_cMHCTRLINT",
  "title" : "Vrijheidsbeperkende maatregelen",
  "status" : "active",
  "experimental" : false,
  "date" : "2026-07-01T12:34:01+00:00",
  "publisher" : "Example Publisher",
  "contact" : [{
    "name" : "Example Publisher",
    "telecom" : [{
      "system" : "url",
      "value" : "http://example.org/example-publisher"
    }]
  }],
  "description" : "Vrijheidsbeperkende maatregelen",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHCTRLINT_0",
    "display" : "Niet geactiveerd: afwezigheid van fixatie, afzonderingskamer of acute control medication.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: keine Fixierung, Isolationszimmer oder akute Kontrolle der Medikation."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : absence de fixation, chambre d'isolement ou contrôle aigu de la médication."
    }]
  },
  {
    "code" : "cMHCTRLINT_1",
    "display" : "Geactiveerd om vrijheidsbeperkende maatregelen te elimineren - personen die niet in een psychiatrische noodsituatie verkeren.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um die Freiheitsbeschränkenden Maßnahmen aufzuheben - Personen die sich nicht in einer akuten psychiatrischen Situation befinden."
    },
    {
      "language" : "fr",
      "value" : "Activé pour éliminer des mesures limitant la liberté - personnes qui ne sont pas en situation d'urgence psychiatrique."
    }]
  },
  {
    "code" : "cMHCTRLINT_2",
    "display" : "Geactiveerd om de behoefte aan vrijheidsbeperkende maatregelen te elimineren - personen in een psychiatrische noodsituatie.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um die Freiheitsbeschränkenden Maßnahmen aufzuheben - Personen die sich in einer akuten psychiatrischen Situation befinden."
    },
    {
      "language" : "fr",
      "value" : "Activé pour éliminer le besoin de mesures limitant la liberté - personnes en situation d'urgence psychiatrique."
    }]
  }]
}

```
