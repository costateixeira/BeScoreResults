# Tabak- en alcoholgebruik - v0.1.0

## CodeSystem: Tabak- en alcoholgebruik 

 
Tabak- en alcoholgebruik 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cadd",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cadd",
  "version" : "0.1.0",
  "name" : "CS_cADD",
  "title" : "Tabak- en alcoholgebruik",
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
  "description" : "Tabak- en alcoholgebruik",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cADD_0",
    "display" : "Niet geactiveerd: geen aanleiding tot stoppen met roken of reduceren van alcoholgebruik.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: kein Grund das Rauchen zu beenden oder den Alkoholkonsum zu reduzieren."
    },
    {
      "language" : "fr",
      "value" : "Non activé : aucune raison d'arrêter de fumer ou de réduire la consommation d'alcool."
    }]
  },
  {
    "code" : "cADD_1",
    "display" : "Geactiveerd wegens dagelijks roken en/of alcoholbehoefte.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: raucht und trinkt regelmäßig Alkohol."
    },
    {
      "language" : "fr",
      "value" : "Activé : fume et consomme de l'alcool quotidiennement."
    }]
  }]
}

```
