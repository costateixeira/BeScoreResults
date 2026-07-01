# Opleiding en werk - v0.1.0

## CodeSystem: Opleiding en werk 

 
Opleiding en werk 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhedemp",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhedemp",
  "version" : "0.1.0",
  "name" : "CS_cMHEDEMP",
  "title" : "Opleiding en werk",
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
  "description" : "Opleiding en werk",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHEDEMP_0",
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
    "code" : "cMHEDEMP_1",
    "display" : "Geactiveerd op hulp om een job te vinden of aan een opleidingsprogramma deel te nemen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: Braucht Unterstützung um eine Arbeitsstelle zu finden oder einem Weiterbildungsprogramm zu folgen."
    },
    {
      "language" : "fr",
      "value" : "Activé : aide pour trouver un job ou participer à un programme de formation."
    }]
  },
  {
    "code" : "cMHEDEMP_2",
    "display" : "Geactiveerd om het risico op werkloosheid of schoolmoeheid te verminderen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um das Risiko einer Arbeitslosigkeit oder Schuldermüdung zu verringern."
    },
    {
      "language" : "fr",
      "value" : "Activé pour diminuer le risque de chômage ou lassitude scolaire."
    }]
  }]
}

```
