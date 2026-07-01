# Criminele activiteiten - v0.1.0

## CodeSystem: Criminele activiteiten 

 
Criminele activiteiten 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhcrim",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhcrim",
  "version" : "0.1.0",
  "name" : "CS_cMHCRIM",
  "title" : "Criminele activiteiten",
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
  "description" : "Criminele activiteiten",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cMHCRIM_0",
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
    "code" : "cMHCRIM_1",
    "display" : "Geactiveerd om het risico op al dan niet gewelddadig crimineel gedrag te beperken.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um das Risiko von kriminellem und gewalttätigem Verhalten zu begrenzen."
    },
    {
      "language" : "fr",
      "value" : "Activé pour limiter le risque de comportement criminel violent ou non-violent."
    }]
  }]
}

```
