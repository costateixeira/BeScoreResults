# Thuisomgeving - v0.1.0

## CodeSystem: Thuisomgeving 

 
Thuisomgeving 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cenvir",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cenvir",
  "version" : "0.1.0",
  "name" : "CS_cENVIR",
  "title" : "Thuisomgeving",
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
  "description" : "Thuisomgeving",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cENVIR_0",
    "display" : "Niet geactiveerd: geen combinatie van een zwakke fysieke of mentale toestand met een problematische woonomgeving.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: keine Kombination einer physischen oder mentalen Situation mit einer problematischen Wohnumgebung."
    },
    {
      "language" : "fr",
      "value" : "Non activé : pas de combinaison d'une situation physique ou mentale précaire avec un environnement problématique."
    }]
  },
  {
    "code" : "cENVIR_1",
    "display" : "Geactiveerd wegens een zwakke fysieke of mentale toestand gecombineerd met een problematische woonomgeving.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: Kombination einer physischen oder mentalen Situation mit einer problematischen Wohnumgebung."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'une combinaison d'une situation physique ou mentale précaire avec un environnement problématique."
    }]
  }]
}

```
