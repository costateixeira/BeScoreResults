# Darmproblemen - v0.1.0

## CodeSystem: Darmproblemen 

 
Darmproblemen 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cbowel",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cbowel",
  "version" : "0.1.0",
  "name" : "CS_cBOWEL",
  "title" : "Darmproblemen",
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
  "description" : "Darmproblemen",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cBOWEL_0",
    "display" : "Niet geactiveerd: eventueel behandelde darmproblemen.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: mögliche Behandlung eines Darmproblems."
    },
    {
      "language" : "fr",
      "value" : "Non activé : traitement éventuel des problèmes d'intestin."
    }]
  },
  {
    "code" : "cBOWEL_1",
    "display" : "Geactiveerd om achteruitgang te voorkomen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um einen Rückfall vorzubeugen."
    },
    {
      "language" : "fr",
      "value" : "Activé pour la prévention du déclin."
    }]
  },
  {
    "code" : "cBOWEL_2",
    "display" : "Geactiveerd op potentiële vooruitgang.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert zur Vorbeugung eines Rückfalls."
    },
    {
      "language" : "fr",
      "value" : "Activé pour un potentiel déclin."
    }]
  }]
}

```
