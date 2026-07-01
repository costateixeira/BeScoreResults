# Communication Scale (sCOMM) - v0.1.0

## CodeSystem: Communication Scale (sCOMM) 

 
Communication Scale (sCOMM) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-scomm",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-scomm",
  "version" : "0.1.0",
  "name" : "CS_sCOMM",
  "title" : "Communication Scale (sCOMM)",
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
  "description" : "Communication Scale (sCOMM)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 9,
  "concept" : [{
    "code" : "sCOMM_0",
    "display" : "Intact",
    "designation" : [{
      "language" : "de",
      "value" : "Intakt"
    },
    {
      "language" : "fr",
      "value" : "Intact"
    }]
  },
  {
    "code" : "sCOMM_1",
    "display" : "Zo goed als intact",
    "designation" : [{
      "language" : "de",
      "value" : "Fast intakt"
    },
    {
      "language" : "fr",
      "value" : "Pratiquement intact"
    }]
  },
  {
    "code" : "sCOMM_2",
    "display" : "Licht verstoord",
    "designation" : [{
      "language" : "de",
      "value" : "Leichter Rückgang"
    },
    {
      "language" : "fr",
      "value" : "Déclin léger"
    }]
  },
  {
    "code" : "sCOMM_3",
    "display" : "Licht tot matig verstoord",
    "designation" : [{
      "language" : "de",
      "value" : "Leichter bis moderater Rückgang"
    },
    {
      "language" : "fr",
      "value" : "Déclin léger à modéré"
    }]
  },
  {
    "code" : "sCOMM_4",
    "display" : "Matig verstoord",
    "designation" : [{
      "language" : "de",
      "value" : "Moderater Rückgang"
    },
    {
      "language" : "fr",
      "value" : "Déclin modéré"
    }]
  },
  {
    "code" : "sCOMM_5",
    "display" : "Matig tot ernstig verstoord",
    "designation" : [{
      "language" : "de",
      "value" : "Moderater bis ernster Rückgang"
    },
    {
      "language" : "fr",
      "value" : "Déclin modéré à important"
    }]
  },
  {
    "code" : "sCOMM_6",
    "display" : "Ernstig verstoord",
    "designation" : [{
      "language" : "de",
      "value" : "Ernster Rückgang"
    },
    {
      "language" : "fr",
      "value" : "Déclin important"
    }]
  },
  {
    "code" : "sCOMM_7",
    "display" : "Ernstig tot zeer ernstig verstoord",
    "designation" : [{
      "language" : "de",
      "value" : "Ernst bis sehr ernster Rückgang"
    },
    {
      "language" : "fr",
      "value" : "Déclin important à très important"
    }]
  },
  {
    "code" : "sCOMM_8",
    "display" : "Zeer ernstig verstoord",
    "designation" : [{
      "language" : "de",
      "value" : "Sehr ernster Rückgang"
    },
    {
      "language" : "fr",
      "value" : "Déclin très important"
    }]
  }]
}

```
