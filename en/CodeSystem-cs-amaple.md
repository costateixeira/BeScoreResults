# Method for Assigning Priority Levels (aMAPLe) - v0.1.0

## CodeSystem: Method for Assigning Priority Levels (aMAPLe) 

 
Method for Assigning Priority Levels (aMAPLe) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-amaple",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-amaple",
  "version" : "0.1.0",
  "name" : "CS_aMAPLE",
  "title" : "Method for Assigning Priority Levels (aMAPLe)",
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
  "description" : "Method for Assigning Priority Levels (aMAPLe)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 5,
  "concept" : [{
    "code" : "aMAPLE_1",
    "display" : "Lage prioriteit",
    "designation" : [{
      "language" : "de",
      "value" : "Geringe Priorität"
    },
    {
      "language" : "fr",
      "value" : "Priorité basse"
    }]
  },
  {
    "code" : "aMAPLE_2",
    "display" : "Milde prioriteit",
    "designation" : [{
      "language" : "de",
      "value" : "Leichte Priorität"
    },
    {
      "language" : "fr",
      "value" : "Priorité faible"
    }]
  },
  {
    "code" : "aMAPLE_3",
    "display" : "Matige prioriteit",
    "designation" : [{
      "language" : "de",
      "value" : "Moderate Priorität"
    },
    {
      "language" : "fr",
      "value" : "Priorité modérée"
    }]
  },
  {
    "code" : "aMAPLE_4",
    "display" : "Hoge prioriteit",
    "designation" : [{
      "language" : "de",
      "value" : "Hohe Priorität"
    },
    {
      "language" : "fr",
      "value" : "Haute priorité"
    }]
  },
  {
    "code" : "aMAPLE_5",
    "display" : "Zeer hoge prioriteit",
    "designation" : [{
      "language" : "de",
      "value" : "Sehr hohe Priorität"
    },
    {
      "language" : "fr",
      "value" : "Très haute priorité"
    }]
  }]
}

```
