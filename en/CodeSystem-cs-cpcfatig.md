# Vermoeidheid - v0.1.0

## CodeSystem: Vermoeidheid 

 
Vermoeidheid 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cpcfatig",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cpcfatig",
  "version" : "0.1.0",
  "name" : "CS_cPCFATIG",
  "title" : "Vermoeidheid",
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
  "description" : "Vermoeidheid",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cPCFATIG_0",
    "display" : "Niet geactiveerd: geen vermoeidheid.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: keine Müdigkeit."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : pas de fatigue."
    }]
  },
  {
    "code" : "cPCFATIG_1",
    "display" : "Geactiveerd wegens een matig risico op vermoeidheid.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von einem mittleren Risiko von Ermüdung."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque modéré de fatigue."
    }]
  },
  {
    "code" : "cPCFATIG_2",
    "display" : "Geactiveerd wegens een ernstig risico op vermoeidheid.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von einem ernsten Risiko von Ermüdung."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque sévère de fatigue."
    }]
  }]
}

```
