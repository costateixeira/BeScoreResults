# Voeding - Palliatieve zorg - v0.1.0

## CodeSystem: Voeding - Palliatieve zorg 

 
Voeding - Palliatieve zorg 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cpcnutr",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cpcnutr",
  "version" : "0.1.0",
  "name" : "CS_cPCNUTR",
  "title" : "Voeding - Palliatieve zorg",
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
  "description" : "Voeding - Palliatieve zorg",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cPCNUTR_0",
    "display" : "Niet geactiveerd: geen gevaar voor ondervoeding.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: keine Gefahr von Mangelernährung."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : aucun danger de malnutrition."
    }]
  },
  {
    "code" : "cPCNUTR_1",
    "display" : "Geactiveerd wegens een laag risico: BMI-score is lager dan 21 maar geen recent gewichtsverlies.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert wegen geringem Risiko: BMI kleiner als 21, aber ohne kürzlichen Gewichtsverlust."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque peu élevé : le score IMC est inférieur à 21 mais il n'y a pas de perte de poids récente."
    }]
  },
  {
    "code" : "cPCNUTR_2",
    "display" : "Geactiveerd wegens een hoog risico: BMI-score is lager dan 21 en gaat gepaard met recent gewichtsverlies.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert wegen erhöhtem Risiko: BMI kleiner als 21 begleitet von kürzlichem Gewichtsverlust."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque élevé : score IMC est inférieur à 21 mais est associé à une perte de poids récente."
    }]
  }]
}

```
