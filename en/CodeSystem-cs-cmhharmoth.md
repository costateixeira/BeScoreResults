# Schade aan anderen - v0.1.0

## CodeSystem: Schade aan anderen 

 
Schade aan anderen 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhharmoth",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhharmoth",
  "version" : "0.1.0",
  "name" : "CS_cMHHARMOTH",
  "title" : "Schade aan anderen",
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
  "description" : "Schade aan anderen",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHHARMOTH_0",
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
    "code" : "cMHHARMOTH_1",
    "display" : "Geactiveerd wegens een matig risico op schade aan anderen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund eines moderaten Risikos der Fremdgefährdung."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque modéré de dommages pour les autres."
    }]
  },
  {
    "code" : "cMHHARMOTH_2",
    "display" : "Geactiveerd wegens een hoog risico op schade aan anderen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund eines hohen Risikos der Fremdgefährdung."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque élevé de dommages pour les autres."
    }]
  }]
}

```
