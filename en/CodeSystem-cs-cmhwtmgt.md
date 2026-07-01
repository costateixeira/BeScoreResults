# Gewichtsmanagement - v0.1.0

## CodeSystem: Gewichtsmanagement 

 
Gewichtsmanagement 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhwtmgt",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhwtmgt",
  "version" : "0.1.0",
  "name" : "CS_cMHWTMGT",
  "title" : "Gewichtsmanagement",
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
  "description" : "Gewichtsmanagement",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHWTMGT_0",
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
    "code" : "cMHWTMGT_1",
    "display" : "Geactiveerd wegens een problematisch eetgedrag.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von problematischem Essensverhalten."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un comportement alimentaire problématique."
    }]
  },
  {
    "code" : "cMHWTMGT_2",
    "display" : "Geactiveerd wegens een afwijkende lichaamsbouw.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund einer anderen Morphologie."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'une morphologie différente."
    }]
  }]
}

```
