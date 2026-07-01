# Pain Scale - Hospital (sHSPAIN) - v0.1.0

## CodeSystem: Pain Scale - Hospital (sHSPAIN) 

 
Pain Scale - Hospital (sHSPAIN) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-shspain",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-shspain",
  "version" : "0.1.0",
  "name" : "CS_sHSPAIN",
  "title" : "Pain Scale - Hospital (sHSPAIN)",
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
  "description" : "Pain Scale - Hospital (sHSPAIN)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 5,
  "concept" : [{
    "code" : "sHSPAIN_0",
    "display" : "Geen pijn",
    "designation" : [{
      "language" : "de",
      "value" : "Keine Schmerzen"
    },
    {
      "language" : "fr",
      "value" : "Pas de douleur"
    }]
  },
  {
    "code" : "sHSPAIN_1",
    "display" : "Pijn aanwezig maar niet in de laatste 3 dagen vertoond.",
    "designation" : [{
      "language" : "de",
      "value" : "Schmerzen vorhanden aber nicht innerhalb der letzten 3 Tage."
    },
    {
      "language" : "fr",
      "value" : "douleur présente mais pas au cours des 3 derniers jours."
    }]
  },
  {
    "code" : "sHSPAIN_2",
    "display" : "Matige pijn in de laatste 3 dagen.",
    "designation" : [{
      "language" : "de",
      "value" : "Moderate Schmerzen innerhalb der letzten 3 Tage."
    },
    {
      "language" : "fr",
      "value" : "Douleur modérée au cours des 3 derniers jours."
    }]
  },
  {
    "code" : "sHSPAIN_3",
    "display" : "Ernstige pijn in de laatste 3 dagen.",
    "designation" : [{
      "language" : "de",
      "value" : "Ernsthafte Schmerzen innerhalb der letzten 3 Tage."
    },
    {
      "language" : "fr",
      "value" : "Douleur sévère au cours des 3 derniers jours."
    }]
  },
  {
    "code" : "sHSPAIN_4",
    "display" : "Vreselijke of ondraaglijke pijn in de laatste 3 dagen.",
    "designation" : [{
      "language" : "de",
      "value" : "Starke nicht aushaltbare Schmerzen innerhalb der letzten 3 Tage."
    },
    {
      "language" : "fr",
      "value" : "Douleur terrible ou atroce au cours des 3 derniers jours."
    }]
  }]
}

```
