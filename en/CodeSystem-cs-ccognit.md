# Cognitieverlies - v0.1.0

## CodeSystem: Cognitieverlies 

 
Cognitieverlies 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-ccognit",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-ccognit",
  "version" : "0.1.0",
  "name" : "CS_cCOGNIT",
  "title" : "Cognitieverlies",
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
  "description" : "Cognitieverlies",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cCOGNIT_0",
    "display" : "Niet geactiveerd.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert."
    },
    {
      "language" : "fr",
      "value" : "Pas activé."
    }]
  },
  {
    "code" : "cCOGNIT_1",
    "display" : "Geactiveerd om het risico op cognitieve achteruitgang te controleren/op te volgen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um das Risiko eines kognitiven Rückfalls zu begleiten oder zu kontrollieren."
    },
    {
      "language" : "fr",
      "value" : "Activé pour suivre/contrôler le risque le déclin cognitif."
    }]
  },
  {
    "code" : "cCOGNIT_2",
    "display" : "Geactiveerd om achteruitgang te voorkomen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um das Risiko eines Rückfalls vorzubeugen."
    },
    {
      "language" : "fr",
      "value" : "Activé pour prévenir le déclin."
    }]
  }]
}

```
