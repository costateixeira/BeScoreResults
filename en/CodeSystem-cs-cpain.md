# Pijn - v0.1.0

## CodeSystem: Pijn 

 
Pijn 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cpain",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cpain",
  "version" : "0.1.0",
  "name" : "CS_cPAIN",
  "title" : "Pijn",
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
  "description" : "Pijn",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cPAIN_0",
    "display" : "Niet geactiveerd: geen lichte of hevige pijn.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: keine leichten oder starken Schmerzen."
    },
    {
      "language" : "fr",
      "value" : "Non activé : pas de douleur légère ou intense."
    }]
  },
  {
    "code" : "cPAIN_1",
    "display" : "Geactiveerd als matige prioriteit wegens dagelijks lichte pijn.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert mit mittlerer Priorität aufgrund von leichten täglichen Schmerzen."
    },
    {
      "language" : "fr",
      "value" : "Activé comme priorité modérée en raison de douleurs quotidiennes légères."
    }]
  },
  {
    "code" : "cPAIN_2",
    "display" : "Geactiveerd als hoge prioriteit wegens hevige, vreselijke of ondraaglijke pijn ongeacht de frequentie.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert mit hoher Priorität aufgrund von starken, heftigen oder nichtaushaltbaren Schmerzen unabhängig von der Frequenz."
    },
    {
      "language" : "fr",
      "value" : "Activé comme priorité élevée en raison de douleurs intenses, terribles ou insupportables indépendamment de la fréquence."
    }]
  }]
}

```
