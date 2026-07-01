# BelRAI - Bewustzijn over zes maand of minder - v0.1.0

## CodeSystem: BelRAI - Bewustzijn over zes maand of minder 

 
De persoon zegt zich ervan bewust te zijn dat hij/zij/die zes maand of minder te leven heeft. 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-belrai-aware-6-months",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-belrai-aware-6-months",
  "version" : "0.1.0",
  "name" : "CS_BelRaiAware6Months",
  "title" : "BelRAI - Bewustzijn over zes maand of minder",
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
  "description" : "De persoon zegt zich ervan bewust te zijn dat hij/zij/die zes maand of minder te leven heeft.",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "aw-no-or-na",
    "display" : "Nee of niet van toepassing"
  },
  {
    "code" : "aw-yes",
    "display" : "Ja"
  }]
}

```
