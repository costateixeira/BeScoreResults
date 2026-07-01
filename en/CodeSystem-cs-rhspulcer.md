# Pressure Ulcer Risk Scale in Hospital (rHSPULCER) - v0.1.0

## CodeSystem: Pressure Ulcer Risk Scale in Hospital (rHSPULCER) 

 
Pressure Ulcer Risk Scale in Hospital (rHSPULCER) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-rhspulcer",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-rhspulcer",
  "version" : "0.1.0",
  "name" : "CS_rHSPULCER",
  "title" : "Pressure Ulcer Risk Scale in Hospital (rHSPULCER)",
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
  "description" : "Pressure Ulcer Risk Scale in Hospital (rHSPULCER)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "rHSPULCER_0",
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
    "code" : "rHSPULCER_1",
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
    "code" : "rHSPULCER_2",
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
