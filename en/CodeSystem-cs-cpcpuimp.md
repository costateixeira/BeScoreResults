# Decubitus - Palliatieve zorg - v0.1.0

## CodeSystem: Decubitus - Palliatieve zorg 

 
Decubitus - Palliatieve zorg 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cpcpuimp",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cpcpuimp",
  "version" : "0.1.0",
  "name" : "CS_cpcPUIMP",
  "title" : "Decubitus - Palliatieve zorg",
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
  "description" : "Decubitus - Palliatieve zorg",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cpcPUIMP_0",
    "display" : "Niet geactiveerd: geen decubitus en/of risicofactoren aanwezig.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: kein Dekubitus und/oder Risiko für einen Dekubitus."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : pas de présence d'escarres et ou des facteurs de risque."
    }]
  },
  {
    "code" : "cpcPUIMP_1",
    "display" : "Geactiveerd wegens een moeilijke verbetering van decubitus.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund einer geringen Chance auf Besserung des Dekubitus."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'une amélioration difficile de l'escarre."
    }]
  },
  {
    "code" : "cpcPUIMP_2",
    "display" : "Geactiveerd wegens meer kans op verbetering van decubitus.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund einer guten Chance auf Besserung des Dekubitus."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de plus de chance d'amélioration de l'escarre."
    }]
  }]
}

```
