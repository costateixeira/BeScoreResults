# ADL Hierarchy Scale – Hospital (sHSADLH) - v0.1.0

## CodeSystem: ADL Hierarchy Scale – Hospital (sHSADLH) 

 
ADL Hierarchy Scale – Hospital (sHSADLH) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-shsadlh",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-shsadlh",
  "version" : "0.1.0",
  "name" : "CS_sHSADLH",
  "title" : "ADL Hierarchy Scale – Hospital (sHSADLH)",
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
  "description" : "ADL Hierarchy Scale – Hospital (sHSADLH)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 7,
  "concept" : [{
    "code" : "sHSADLH_0",
    "display" : "Zelfstandig",
    "designation" : [{
      "language" : "de",
      "value" : "Selbstständig"
    },
    {
      "language" : "fr",
      "value" : "Autonome"
    }]
  },
  {
    "code" : "sHSADLH_1",
    "display" : "Toezicht vereist",
    "designation" : [{
      "language" : "de",
      "value" : "Begleitung"
    },
    {
      "language" : "fr",
      "value" : "Surveillance exigée"
    }]
  },
  {
    "code" : "sHSADLH_2",
    "display" : "Beperkte hulp vereist",
    "designation" : [{
      "language" : "de",
      "value" : "Begrenzte Unterstützung"
    },
    {
      "language" : "fr",
      "value" : "Aide limitée exigée"
    }]
  },
  {
    "code" : "sHSADLH_3",
    "display" : "Uitgebreide hulp vereist - 1",
    "designation" : [{
      "language" : "de",
      "value" : "Verstärkte Unterstützung -1"
    },
    {
      "language" : "fr",
      "value" : "Aide élargie exigée -1"
    }]
  },
  {
    "code" : "sHSADLH_4",
    "display" : "Uitgebreide hulp vereist - 2",
    "designation" : [{
      "language" : "de",
      "value" : "Maximale Unterstützung"
    },
    {
      "language" : "fr",
      "value" : "Aide élargie exigée -2"
    }]
  },
  {
    "code" : "sHSADLH_5",
    "display" : "Afhankelijk",
    "designation" : [{
      "language" : "de",
      "value" : "Abhängigkeit"
    },
    {
      "language" : "fr",
      "value" : "Dépendant"
    }]
  },
  {
    "code" : "sHSADLH_6",
    "display" : "Volledig afhankelijk",
    "designation" : [{
      "language" : "de",
      "value" : "Vollständige Abhängigkeit "
    },
    {
      "language" : "fr",
      "value" : "Totalement dépendant"
    }]
  }]
}

```
