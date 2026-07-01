# Pressure Ulcer Risk Scale (sPURS) - v0.1.0

## CodeSystem: Pressure Ulcer Risk Scale (sPURS) 

 
Pressure Ulcer Risk Scale (sPURS) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-spurs",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-spurs",
  "version" : "0.1.0",
  "name" : "CS_sPURS",
  "title" : "Pressure Ulcer Risk Scale (sPURS)",
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
  "description" : "Pressure Ulcer Risk Scale (sPURS)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "sPURS_0",
    "display" : "Zeer laag risico",
    "designation" : [{
      "language" : "de",
      "value" : "Sehr geringes Risiko"
    },
    {
      "language" : "fr",
      "value" : "Risque très faible"
    }]
  },
  {
    "code" : "sPURS_3",
    "display" : "Matig risico",
    "designation" : [{
      "language" : "de",
      "value" : "Moderates Risiko"
    },
    {
      "language" : "fr",
      "value" : "Risque modéré"
    }]
  }]
}

```
