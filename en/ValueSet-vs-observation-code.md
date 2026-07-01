# BelRAI - Observation codes - v0.1.0

## ValueSet: BelRAI - Observation codes 

 
Codes identifying each BelRAI scoring scale/screener, used as Observation.code. 

 **References** 

This value set is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

### Logical Definition (CLD)

 

### Expansion

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "ValueSet",
  "id" : "vs-observation-code",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/ValueSet/vs-observation-code",
  "version" : "0.1.0",
  "name" : "VS_ObservationCode",
  "title" : "BelRAI - Observation codes",
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
  "description" : "Codes identifying each BelRAI scoring scale/screener, used as Observation.code.",
  "compose" : {
    "include" : [{
      "system" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-observation-code"
    }]
  }
}

```
