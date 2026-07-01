# Zelfmoordgedrag en opzettelijke zelfverwonding - v0.1.0

## CodeSystem: Zelfmoordgedrag en opzettelijke zelfverwonding 

 
Zelfmoordgedrag en opzettelijke zelfverwonding 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhselfha",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhselfha",
  "version" : "0.1.0",
  "name" : "CS_cMHSELFHA",
  "title" : "Zelfmoordgedrag en opzettelijke zelfverwonding",
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
  "description" : "Zelfmoordgedrag en opzettelijke zelfverwonding",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHSELFHA_0",
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
    "code" : "cMHSELFHA_1",
    "display" : "Geactiveerd wegens een matig risico op zelfverwonding.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund eines moderaten Risikos der Selbstverletzung."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque modéré d'automutilation."
    }]
  },
  {
    "code" : "cMHSELFHA_2",
    "display" : "Geactiveerd wegens een hoog risico op zelfverwonding.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund eines hohen Risikos der Selbstverletzung. "
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque élevé d'automutilation."
    }]
  }]
}

```
