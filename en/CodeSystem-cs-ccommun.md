# Communicatie - v0.1.0

## CodeSystem: Communicatie 

 
Communicatie 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-ccommun",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-ccommun",
  "version" : "0.1.0",
  "name" : "CS_cCOMMUN",
  "title" : "Communicatie",
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
  "description" : "Communicatie",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cCOMMUN_0",
    "display" : "Niet geactiveerd: functioneel herstel ter preventie van achteruitgang is klinisch gezien geen geschikt zorgdoel.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: Die Wiederherstellung oder der Erhalt der Funktionen zur Vorbeugung eines Rückfalls ist kein angepasstes Pflegeziel."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : récupération fonctionnelle pour prévenir le déclin n'est pas d'un point de vue clinique un objectif de soins approprié."
    }]
  },
  {
    "code" : "cCOMMUN_1",
    "display" : "Geactiveerd op potentiële vooruitgang.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: Möglichkeit der Verbesserung."
    },
    {
      "language" : "fr",
      "value" : "Activé : potentiel d'amélioration."
    }]
  },
  {
    "code" : "cCOMMUN_2",
    "display" : "Geactiveerd om achteruitgang te voorkomen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um einen Rückfall vorzubeugen."
    },
    {
      "language" : "fr",
      "value" : "Activé pour prévenir le déclin."
    }]
  }]
}

```
