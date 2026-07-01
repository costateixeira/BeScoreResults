# BelRAI - Geschatte levensverwachting - v0.1.0

## CodeSystem: BelRAI - Geschatte levensverwachting 

 
Geschatte resterende levensverwachting vanaf de beoordelingsreferentiedatum. 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-belrai-life-expectancy",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-belrai-life-expectancy",
  "version" : "0.1.0",
  "name" : "CS_BelRaiLifeExpectancy",
  "title" : "BelRAI - Geschatte levensverwachting",
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
  "description" : "Geschatte resterende levensverwachting vanaf de beoordelingsreferentiedatum.",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 4,
  "concept" : [{
    "code" : "le-imminent",
    "display" : "Nakend overlijden (binnen enkele dagen)"
  },
  {
    "code" : "le-under-6w",
    "display" : "Minder dan 6 weken"
  },
  {
    "code" : "le-6w-to-6mo",
    "display" : "6 weken of langer, maar minder dan 6 maanden"
  },
  {
    "code" : "le-6mo-plus",
    "display" : "6 maanden of langer"
  }]
}

```
