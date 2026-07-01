# Pijn - Ziekenhuis - v0.1.0

## CodeSystem: Pijn - Ziekenhuis 

 
Pijn - Ziekenhuis 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-chspain",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-chspain",
  "version" : "0.1.0",
  "name" : "CS_cHSPAIN",
  "title" : "Pijn - Ziekenhuis",
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
  "description" : "Pijn - Ziekenhuis",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cHSPAIN_0",
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
    "code" : "cHSPAIN_1",
    "display" : "Geactiveerd wegens een matig verbeteringspotentieel.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund eines mittleren Verbesserungspotenzials."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un potentiel d'amélioration modéré."
    }]
  },
  {
    "code" : "cHSPAIN_2",
    "display" : "Geactiveerd wegens een hoog verbeteringspotentieel.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund eines hohen Verbesserungspotenzials."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un potentiel d'amélioration élevé."
    }]
  }]
}

```
