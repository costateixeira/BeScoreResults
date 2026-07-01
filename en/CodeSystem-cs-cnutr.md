# Ondervoeding - v0.1.0

## CodeSystem: Ondervoeding 

 
Ondervoeding 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cnutr",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cnutr",
  "version" : "0.1.0",
  "name" : "CS_cNUTR",
  "title" : "Ondervoeding",
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
  "description" : "Ondervoeding",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cNUTR_0",
    "display" : "Niet geactiveerd: BMI-score = 22 of meer, geen gevaar voor ondervoeding.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: BMI-Score = 22 oder mehr, keine Gefahr von Mangelernährung."
    },
    {
      "language" : "fr",
      "value" : "Non activé : score IMC = 22 ou plus, pas de danger de malnutrition."
    }]
  },
  {
    "code" : "cNUTR_1",
    "display" : "Geactiveerd wegens matig risico (BMI-score = 19 tot 21) zonder gevaar voor plots overlijden.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund eines mittleren Risikos(BMI - Score = 19 bis 21) ohne Gefahr eines plötzlichen Todes."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque modéré (Score IMC = 19 à 21) sans risque morbide."
    }]
  },
  {
    "code" : "cNUTR_2",
    "display" : "Geactiveerd wegens hoog risico (BMI-score = lager dan 19) zonder gevaar voor plots overlijden.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund eines hohen Risikos (BMI-Score = kleiner als 19) ohne Gefahr eines plötzlichen Todes."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque élevé (Score IMC = inférieur à 19) sans risque morbide."
    }]
  }]
}

```
