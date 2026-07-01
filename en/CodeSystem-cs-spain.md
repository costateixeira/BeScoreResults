# Pain Scale (sPAIN) - v0.1.0

## CodeSystem: Pain Scale (sPAIN) 

 
Pain Scale (sPAIN) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-spain",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-spain",
  "version" : "0.1.0",
  "name" : "CS_sPAIN",
  "title" : "Pain Scale (sPAIN)",
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
  "description" : "Pain Scale (sPAIN)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 5,
  "concept" : [{
    "code" : "sPAIN_0",
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
    "code" : "sPAIN_1",
    "display" : "Minder dan dagelijks pijn",
    "designation" : [{
      "language" : "de",
      "value" : "Schmerzen (nicht täglich)"
    },
    {
      "language" : "fr",
      "value" : "Douleur non journalière"
    }]
  },
  {
    "code" : "sPAIN_2",
    "display" : "Dagelijks matige pijn ",
    "designation" : [{
      "language" : "de",
      "value" : "Tägliche mittlere Schmerzen"
    },
    {
      "language" : "fr",
      "value" : "Douleur journalière modérée"
    }]
  },
  {
    "code" : "sPAIN_3",
    "display" : "Dagelijks ernstige pijn",
    "designation" : [{
      "language" : "de",
      "value" : "Tägliche starke Schmerzen"
    },
    {
      "language" : "fr",
      "value" : "Douleur journalière sévère"
    }]
  },
  {
    "code" : "sPAIN_4",
    "display" : "Dagelijks vreselijke of ondraaglijke pijn",
    "designation" : [{
      "language" : "de",
      "value" : "Tägliche nichtaushaltbare Schmerzen"
    },
    {
      "language" : "fr",
      "value" : "Douleur journalière atroce ou insupportable"
    }]
  }]
}

```
