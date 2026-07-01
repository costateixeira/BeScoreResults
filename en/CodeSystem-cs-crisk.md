# Kans op opname in een voorziening - v0.1.0

## CodeSystem: Kans op opname in een voorziening 

 
Kans op opname in een voorziening 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-crisk",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-crisk",
  "version" : "0.1.0",
  "name" : "CS_cRISK",
  "title" : "Kans op opname in een voorziening",
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
  "description" : "Kans op opname in een voorziening",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cRISK_0",
    "display" : "Niet geactiveerd: geen functionele achteruitgang met een verhoogd risico op opname in een voorziening tijdens de komende maanden.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: Kein funktioneller Rückfall mit dem Risiko einer stationären Aufnahme in den nächsten Monaten."
    },
    {
      "language" : "fr",
      "value" : "Non activé : pas de déclin fonctionnel avec un risque accru d'admission dans une institution au cours des mois prochains."
    }]
  },
  {
    "code" : "cRISK_1",
    "display" : "Geactiveerd wegens functionele achteruitgang met een verhoogd risico op opname in een voorziening tijdens de komende maanden.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: funktioneller Rückfall mit dem Risiko einer möglichen stationären Aufnahme in den nächsten Monaten."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un déclin fonctionnel avec un risque accru d'admission dans une institution au cours des mois prochains."
    }]
  }]
}

```
