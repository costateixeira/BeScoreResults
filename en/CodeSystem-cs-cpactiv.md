# Bevordering van de lichaamsbeweging - v0.1.0

## CodeSystem: Bevordering van de lichaamsbeweging 

 
Bevordering van de lichaamsbeweging 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cpactiv",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cpactiv",
  "version" : "0.1.0",
  "name" : "CS_cPACTIV",
  "title" : "Bevordering van de lichaamsbeweging",
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
  "description" : "Bevordering van de lichaamsbeweging",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cPACTIV_0",
    "display" : "Niet geactiveerd: geen mogelijkheid tot verbetering.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: keine Möglichkeit der Verbesserung."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : pas de possibilité d'amélioration."
    }]
  },
  {
    "code" : "cPACTIV_1",
    "display" : "Geactiveerd op de mogelijkheid tot verbetering.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: Möglichkeit der Verbesserung."
    },
    {
      "language" : "fr",
      "value" : "Activé : possibilité d’amélioration."
    }]
  }]
}

```
