# Activiteiten - v0.1.0

## CodeSystem: Activiteiten 

 
Activiteiten 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cactiv",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cactiv",
  "version" : "0.1.0",
  "name" : "CS_cACTIV",
  "title" : "Activiteiten",
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
  "description" : "Activiteiten",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cACTIV_0",
    "display" : "Niet geactiveerd: sociaal actief en betrokken of niet in staat om aan dagelijkse besluitvorming te doen.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: sozialaktiv und in alltägliche Entscheidungen eingebunden bzw. nicht in der Lage diese zu treffen."
    },
    {
      "language" : "fr",
      "value" : "Non activé : socialement actif et impliqué ou incapable de prendre des décisions quotidiennes."
    }]
  },
  {
    "code" : "cACTIV_1",
    "display" : "Geactiveerd wegens meestal niet betrokken bij sociale of andere activiteiten niettegenstaande enige cognitieve reserve om aan dagelijkse besluitvorming te doen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: nicht sozialaktiv und aufgrund von kognitiven Einschränkungen nicht in alltägliche Entscheidungen eingebunden."
    },
    {
      "language" : "fr",
      "value" : "Activé : ne participe généralement pas à des activités sociales ou autres malgré la capacité cognitive pour prendre des décisions quotidiennes."
    }]
  }]
}

```
