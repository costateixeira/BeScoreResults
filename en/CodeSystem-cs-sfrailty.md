# Frailty Scale (sFrailty) - v0.1.0

## CodeSystem: Frailty Scale (sFrailty) 

 
Frailty Scale (sFrailty) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-sfrailty",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-sfrailty",
  "version" : "0.1.0",
  "name" : "CS_sFRAILTY",
  "title" : "Frailty Scale (sFrailty)",
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
  "description" : "Frailty Scale (sFrailty)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "sFRAILTY_0",
    "display" : "Persoon is niet kwetsbaar",
    "designation" : [{
      "language" : "de",
      "value" : "Die Person ist nicht schutzbedürftig"
    },
    {
      "language" : "fr",
      "value" : "La personne n'est pas vulnérable"
    }]
  },
  {
    "code" : "sFRAILTY_1",
    "display" : "Persoon is kwetsbaar",
    "designation" : [{
      "language" : "de",
      "value" : "Die Person ist schutzbedürftig"
    },
    {
      "language" : "fr",
      "value" : "La personne est vulnérable"
    }]
  }]
}

```
