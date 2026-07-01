# Stemming - v0.1.0

## CodeSystem: Stemming 

 
Stemming 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmood",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmood",
  "version" : "0.1.0",
  "name" : "CS_cMOOD",
  "title" : "Stemming",
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
  "description" : "Stemming",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMOOD_0",
    "display" : "Niet geactiveerd: DRS-score = nul.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: DRS-score = 0."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : score DRS = 0."
    }]
  },
  {
    "code" : "cMOOD_1",
    "display" : "Geactiveerd wegens laag risico: DRS-score = één of twee.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert wegen leichtem Risiko: DRS-score = 1 oder 2."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque faible : score DRS = 1 ou 2."
    }]
  },
  {
    "code" : "cMOOD_2",
    "display" : "Geactiveerd wegens hoog risico: DRS-score = drie of hoger.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert wegen hohem Risiko: DRS-score = 3 oder mehr."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque élevé : score DRS = 3 ou +."
    }]
  }]
}

```
