# Falls Risk in Hospital (rHSFALLS) - v0.1.0

## CodeSystem: Falls Risk in Hospital (rHSFALLS) 

 
Falls Risk in Hospital (rHSFALLS) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-rhsfalls",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-rhsfalls",
  "version" : "0.1.0",
  "name" : "CS_rHSFALLS",
  "title" : "Falls Risk in Hospital (rHSFALLS)",
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
  "description" : "Falls Risk in Hospital (rHSFALLS)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "rHSFALLS_0",
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
    "code" : "rHSFALLS_1",
    "display" : "Matig risico",
    "designation" : [{
      "language" : "de",
      "value" : "Moderates Risiko"
    },
    {
      "language" : "fr",
      "value" : "Risque modéré"
    }]
  },
  {
    "code" : "rHSFALLS_2",
    "display" : "Hoog risico",
    "designation" : [{
      "language" : "de",
      "value" : "Hohes Risiko"
    },
    {
      "language" : "fr",
      "value" : "Risque élevé"
    }]
  }]
}

```
