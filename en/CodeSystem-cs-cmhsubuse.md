# Middelengebruik - v0.1.0

## CodeSystem: Middelengebruik 

 
Middelengebruik 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhsubuse",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhsubuse",
  "version" : "0.1.0",
  "name" : "CS_cMHSUBUSE",
  "title" : "Middelengebruik",
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
  "description" : "Middelengebruik",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHSUBUSE_0",
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
    "code" : "cMHSUBUSE_1",
    "display" : "Geactiveerd wegens een voorgeschiedenis van problematisch middelengebruik.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von vergangenem Missbrauch von Substanzen."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'antécédents d'usage problématique de substances."
    }]
  },
  {
    "code" : "cMHSUBUSE_2",
    "display" : "Geactiveerd wegens het huidige problematisch middelengebruik.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von aktuellem Missbrauch von Substanzen."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de l'usage problématique actuel de substances."
    }]
  }]
}

```
