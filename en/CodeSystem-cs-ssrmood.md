# Self-reported Mood Scale - v0.1.0

## CodeSystem: Self-reported Mood Scale 

 
Self-reported Mood Scale 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-ssrmood",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-ssrmood",
  "version" : "0.1.0",
  "name" : "CS_sSRMOOD",
  "title" : "Self-reported Mood Scale",
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
  "description" : "Self-reported Mood Scale",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 4,
  "concept" : [{
    "code" : "sSRMOOD_0",
    "display" : "Geen verstoring van de gemoedstoestand ",
    "designation" : [{
      "language" : "de",
      "value" : "keine"
    },
    {
      "language" : "fr",
      "value" : "Pas de perturbation de l’humeur"
    }]
  },
  {
    "code" : "sSRMOOD_range_1_2",
    "display" : "1-2 Milde verstoring van de gemoedstoestand ",
    "designation" : [{
      "language" : "de",
      "value" : "1-2 mild"
    },
    {
      "language" : "fr",
      "value" : "1-2 Perturbation légère de l’humeur"
    }]
  },
  {
    "code" : "sSRMOOD_range_3_4",
    "display" : "3-4 Matige verstoring van de gemoedstoestand ",
    "designation" : [{
      "language" : "de",
      "value" : "3-4 mäßig"
    },
    {
      "language" : "fr",
      "value" : "3-4 Perturbation modérée de l’humeur"
    }]
  },
  {
    "code" : "sSRMOOD_range_5_9",
    "display" : "5-9 Ernstige verstoring van de gemoedstoestand ",
    "designation" : [{
      "language" : "de",
      "value" : "5-9 schwer"
    },
    {
      "language" : "fr",
      "value" : "5-9 Perturbation sévère de l’humeur"
    }]
  }]
}

```
