# Slaapstoornis - Palliatieve zorg - v0.1.0

## CodeSystem: Slaapstoornis - Palliatieve zorg 

 
Slaapstoornis - Palliatieve zorg 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cpcsleep",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cpcsleep",
  "version" : "0.1.0",
  "name" : "CS_cPCSLEEP",
  "title" : "Slaapstoornis - Palliatieve zorg",
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
  "description" : "Slaapstoornis - Palliatieve zorg",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cPCSLEEP_0",
    "display" : "Niet geactiveerd: geen slaapstoornissen.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: keine Schlafstörungen."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : pas de troubles du sommeil."
    }]
  },
  {
    "code" : "cPCSLEEP_1",
    "display" : "Geactiveerd wegens minder kans op verbetering.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund einer geringen Chance auf Besserung."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de moins de chance d'amélioration."
    }]
  },
  {
    "code" : "cPCSLEEP_2",
    "display" : "Geactiveerd wegens een grote kans op verbetering.",
    "designation" : [{
      "language" : "de",
      "value" : " Aktiviert aufgrund einer großen Chance auf Besserung."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de plus de chance d'amélioration."
    }]
  }]
}

```
