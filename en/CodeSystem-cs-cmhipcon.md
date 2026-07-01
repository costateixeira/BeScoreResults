# Intermenselijke conflicten - v0.1.0

## CodeSystem: Intermenselijke conflicten 

 
Intermenselijke conflicten 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhipcon",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhipcon",
  "version" : "0.1.0",
  "name" : "CS_cMHIPCON",
  "title" : "Intermenselijke conflicten",
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
  "description" : "Intermenselijke conflicten",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHIPCON_0",
    "display" : "Niet geactiveerd",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert"
    },
    {
      "language" : "fr",
      "value" : "Pas activé"
    }]
  },
  {
    "code" : "cMHIPCON_1",
    "display" : "Geactiveerd om conflicten binnen specifieke relaties te beperken.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um Konflikte in spezifischen Beziehungen zu begrenzen."
    },
    {
      "language" : "fr",
      "value" : "Activé pour limiter les conflits dans des relations spécifiques."
    }]
  },
  {
    "code" : "cMHIPCON_2",
    "display" : "Geactiveerd om wijdverspreide conflicten te beperken.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um Konflikte generell zu begrenzen."
    },
    {
      "language" : "fr",
      "value" : "Activé pour limiter les conflits généralisés."
    }]
  }]
}

```
