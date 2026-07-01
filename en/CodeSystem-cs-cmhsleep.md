# Slaapstoornissen - Mentale gezondheid - v0.1.0

## CodeSystem: Slaapstoornissen - Mentale gezondheid 

 
Slaapstoornissen - Mentale gezondheid 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhsleep",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhsleep",
  "version" : "0.1.0",
  "name" : "CS_cMHSLEEP",
  "title" : "Slaapstoornissen - Mentale gezondheid",
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
  "description" : "Slaapstoornissen - Mentale gezondheid",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHSLEEP_0",
    "display" : "Niet geactiveerd",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert"
    },
    {
      "language" : "fr",
      "value" : "Pas activé"
    }]
  },
  {
    "code" : "cMHSLEEP_1",
    "display" : "Geactiveerd wegens slaapstoornissen en een matige cognitieve stoornis.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von Schlafstörungen und moderaten kognitiven Störungen."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de troubles du sommeil et d'une déficience cognitive modérée."
    }]
  },
  {
    "code" : "cMHSLEEP_2",
    "display" : "Geactiveerd wegens slaapstoornissen en een ernstige cognitieve stoornis.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von Schlafstörungen und ernsten kognitiven Störungen."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de troubles du sommeil et d'une déficience cognitive sévère."
    }]
  }]
}

```
