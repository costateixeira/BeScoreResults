# Decubitus - Ziekenhuis - v0.1.0

## CodeSystem: Decubitus - Ziekenhuis 

 
Decubitus - Ziekenhuis 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cphspulcer",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cphspulcer",
  "version" : "0.1.0",
  "name" : "CS_cpHSPULCER",
  "title" : "Decubitus - Ziekenhuis",
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
  "description" : "Decubitus - Ziekenhuis",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cpHSPULCER_0",
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
    "code" : "cpHSPULCER_1",
    "display" : "Geactiveerd wegens een matig risico op decubitus.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund eines moderaten Risikos auf einen Dekubitus."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison du risque modéré d'escarres."
    }]
  },
  {
    "code" : "cpHSPULCER_2",
    "display" : "Geactiveerd wegens een hoog risico op decubitus.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund eines hohen Risikos auf einen Dekubitus."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison du risque élevé d'escarres."
    }]
  }]
}

```
