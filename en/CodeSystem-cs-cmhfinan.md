# Persoonlijke financiën - v0.1.0

## CodeSystem: Persoonlijke financiën 

 
Persoonlijke financiën 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhfinan",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhfinan",
  "version" : "0.1.0",
  "name" : "CS_cMHFINAN",
  "title" : "Persoonlijke financiën",
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
  "description" : "Persoonlijke financiën",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHFINAN_0",
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
    "code" : "cMHFINAN_1",
    "display" : "Geactiveerd wegens het onvermogen om de persoonlijke financiën te beheren.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert wegen der Unfähigkeit die eigenen finanziellen Angelegenheiten zu regeln. "
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'une incapacité à gérer des finances personnelles."
    }]
  },
  {
    "code" : "cMHFINAN_2",
    "display" : "Geactiveerd wegens financiële moeilijkheden.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von finanziellen Schwierigkeiten."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de difficultés financières."
    }]
  }]
}

```
