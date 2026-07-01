# Risk of Delirium in Hospital (rHSDELIRIUM) - v0.1.0

## CodeSystem: Risk of Delirium in Hospital (rHSDELIRIUM) 

 
Risk of Delirium in Hospital (rHSDELIRIUM) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-rhsdelirium",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-rhsdelirium",
  "version" : "0.1.0",
  "name" : "CS_rHSDELIRIUM",
  "title" : "Risk of Delirium in Hospital (rHSDELIRIUM)",
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
  "description" : "Risk of Delirium in Hospital (rHSDELIRIUM)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "rHSDELIRIUM_0",
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
    "code" : "rHSDELIRIUM_1",
    "display" : "Geactiveerd",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert"
    },
    {
      "language" : "fr",
      "value" : "Activé"
    }]
  }]
}

```
