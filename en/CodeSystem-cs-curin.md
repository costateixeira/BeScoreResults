# Urine-incontinentie - v0.1.0

## CodeSystem: Urine-incontinentie 

 
Urine-incontinentie 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-curin",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-curin",
  "version" : "0.1.0",
  "name" : "CS_cURIN",
  "title" : "Urine-incontinentie",
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
  "description" : "Urine-incontinentie",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 4,
  "concept" : [{
    "code" : "cURIN_0",
    "display" : "Niet geactiveerd : zwakke besluitvorming en/of beperkte cognitieve vaardigheden bij het begin van het onderzoek.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: schwache Entscheidungsfindung und oder Einschränkungen der kognitiven Fähigkeiten bei dem Beginn einer Recherche."
    },
    {
      "language" : "fr",
      "value" : "Non activé : processus décisionnel faible et/ou restrictions des aptitudes cognitives lors du début de la recherche."
    }]
  },
  {
    "code" : "cURIN_1",
    "display" : "Niet geactiveerd: continent bij het begin van het onderzoek.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: kontinent bei dem Beginn einer Recherche."
    },
    {
      "language" : "fr",
      "value" : "Non activé : continent au début de la recherche."
    }]
  },
  {
    "code" : "cURIN_2",
    "display" : "Geactiveerd om achteruitgang te voorkomen: hogere mate van achteruitgang verwacht.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um einen Rückfall vorzubeugen: starker Rückfall erwartet."
    },
    {
      "language" : "fr",
      "value" : "Activé pour prévenir le declin : plus haut degré de declin attendu."
    }]
  },
  {
    "code" : "cURIN_3",
    "display" : "Geactiveerd om de blaasfunctie te bevorderen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert zur Verbesserung der Blasenfunktionen."
    },
    {
      "language" : "fr",
      "value" : "Activé pour améliorer la fonction urinaire."
    }]
  }]
}

```
