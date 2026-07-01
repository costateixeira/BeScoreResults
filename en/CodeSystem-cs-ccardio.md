# Hart en ademhaling - v0.1.0

## CodeSystem: Hart en ademhaling 

 
Hart en ademhaling 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-ccardio",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-ccardio",
  "version" : "0.1.0",
  "name" : "CS_cCARDIO",
  "title" : "Hart en ademhaling",
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
  "description" : "Hart en ademhaling",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cCARDIO_0",
    "display" : "Niet geactiveerd: er komen geen cardiorespiratoire symptomen voor.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: keine kardio-pulmonalen Symptome."
    },
    {
      "language" : "fr",
      "value" : "Non activé : aucun symptôme cardio-respiratoire."
    }]
  },
  {
    "code" : "cCARDIO_1",
    "display" : "Geactiveerd wegens één of meerdere cardiorespiratoire symptomen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund einem oder von mehreren kardio-pulmonalen Symptomen."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de la présence d'un ou plusieurs symptômes cardio-respiratoires."
    }]
  }]
}

```
