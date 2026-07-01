# Depression Screener (aHSDEPRESSION) - v0.1.0

## CodeSystem: Depression Screener (aHSDEPRESSION) 

 
Depression Screener (aHSDEPRESSION) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-ahsdepression",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-ahsdepression",
  "version" : "0.1.0",
  "name" : "CS_aHSDEPRESSION",
  "title" : "Depression Screener (aHSDEPRESSION)",
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
  "description" : "Depression Screener (aHSDEPRESSION)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "aHSDEPRESSION_0",
    "display" : "Negatief",
    "designation" : [{
      "language" : "de",
      "value" : "Negativ"
    },
    {
      "language" : "fr",
      "value" : "Négatif"
    }]
  },
  {
    "code" : "aHSDEPRESSION_1",
    "display" : "Positief",
    "designation" : [{
      "language" : "de",
      "value" : "Positiv"
    },
    {
      "language" : "fr",
      "value" : "Positif"
    }]
  }]
}

```
