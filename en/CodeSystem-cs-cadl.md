# Activiteiten van het dagelijks leven (ADL) - v0.1.0

## CodeSystem: Activiteiten van het dagelijks leven (ADL) 

 
Activiteiten van het dagelijks leven (ADL) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cadl",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cadl",
  "version" : "0.1.0",
  "name" : "CS_cADL",
  "title" : "Activiteiten van het dagelijks leven (ADL)",
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
  "description" : "Activiteiten van het dagelijks leven (ADL)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cADL_0",
    "display" : "Niet geactiveerd: het herstellen of het behouden van de functionele status om een ADL-terugval te voorkomen is geen prioriteit.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: Es ist nicht prioritär; die Funktionen wiederherzustellen oder zu erhalten um einen Rückfall vorzubeugen (insbesondere in Bezug auf die ADLs)."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : le rétablissement ou le maintien du statut fonctionnel n’est pas une priorité pour prévenir une rechute dans les AVQ."
    }]
  },
  {
    "code" : "cADL_1",
    "display" : "Geactiveerd om achteruitgang te voorkomen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um einen Rückfall vorzubeugen."
    },
    {
      "language" : "fr",
      "value" : "Activé pour prévenir un déclin."
    }]
  },
  {
    "code" : "cADL_2",
    "display" : "Geactiveerd op de mogelijkheid tot verbetering.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: Möglichkeit der Verbesserung."
    },
    {
      "language" : "fr",
      "value" : "Activé : possibilité d'amélioration."
    }]
  }]
}

```
