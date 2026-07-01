# Traumatische levensgebeurtenissen - v0.1.0

## CodeSystem: Traumatische levensgebeurtenissen 

 
Traumatische levensgebeurtenissen 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhtrauma",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhtrauma",
  "version" : "0.1.0",
  "name" : "CS_cMHTRAUMA",
  "title" : "Traumatische levensgebeurtenissen",
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
  "description" : "Traumatische levensgebeurtenissen",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHTRAUMA_0",
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
    "code" : "cMHTRAUMA_1",
    "display" : "Geactiveerd om de impact van eerdere traumatische levensgebeurtenissen te beperken.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um Einflüsse von früheren traumatischen Erlebnissen einzuschränken."
    },
    {
      "language" : "fr",
      "value" : "Activé pour limiter l'impact des événements de la vie traumatiques antérieurs."
    }]
  },
  {
    "code" : "cMHTRAUMA_2",
    "display" : "Geactiveerd om een pertinente veiligheidsbekommernis aan te pakken.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um ein hohes Sicherheitsrisiko zu behandeln."
    },
    {
      "language" : "fr",
      "value" : "Activé pour répondre à un problème de sécurité pertinent."
    }]
  }]
}

```
