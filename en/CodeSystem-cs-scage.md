# Addictions and Substance Use Scale (sCAGE) - v0.1.0

## CodeSystem: Addictions and Substance Use Scale (sCAGE) 

 
Scores van 2 of meer (op een schaal van 0 tot 4) duiden op een potentieel probleem met betrekking tot middelengebruik. 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-scage",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-scage",
  "version" : "0.1.0",
  "name" : "CS_sCAGE",
  "title" : "Addictions and Substance Use Scale (sCAGE)",
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
  "description" : "Scores van 2 of meer (op een schaal van 0 tot 4) duiden op een potentieel probleem met betrekking tot middelengebruik.",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "sCAGE_interval_0_2",
    "display" : "0-2",
    "designation" : [{
      "language" : "de",
      "value" : "0-2"
    },
    {
      "language" : "fr",
      "value" : "0-2"
    }]
  },
  {
    "code" : "sCAGE_interval_2_5",
    "display" : "2-5",
    "designation" : [{
      "language" : "de",
      "value" : "2-5"
    },
    {
      "language" : "fr",
      "value" : "2-5"
    }]
  }]
}

```
