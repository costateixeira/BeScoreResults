# Depression Rating Scale (sDRS) - v0.1.0

## CodeSystem: Depression Rating Scale (sDRS) 

 
Depression Rating Scale (sDRS) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-sdrs",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-sdrs",
  "version" : "0.1.0",
  "name" : "CS_sDRS",
  "title" : "Depression Rating Scale (sDRS)",
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
  "description" : "Depression Rating Scale (sDRS)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 1,
  "concept" : [{
    "code" : "sDRS_range_0_14",
    "display" : "0-14 Hoe hoger de score (op een schaal van 0-14) hoe waarschijnlijker de aanwezigheid van een depressiestoornis.",
    "designation" : [{
      "language" : "de",
      "value" : "0-14 Je höher der Score ist (auf der Skala 0-14), desto höher ist die Wahrscheinlichkeit einer Depression oder einer depressiven Verstimmung."
    },
    {
      "language" : "fr",
      "value" : "0-14 Plus le score est élevé (sur une échelle de 0 à 14), plus il est probable qu'un trouble dépressif soit présent."
    }]
  }]
}

```
