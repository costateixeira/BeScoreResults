# Mantelzorg - Mentale gezondheid - v0.1.0

## CodeSystem: Mantelzorg - Mentale gezondheid 

 
Mantelzorg - Mentale gezondheid 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhinfsupp",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhinfsupp",
  "version" : "0.1.0",
  "name" : "CS_cMHINFSUPP",
  "title" : "Mantelzorg - Mentale gezondheid",
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
  "description" : "Mantelzorg - Mentale gezondheid",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHINFSUPP_0",
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
    "code" : "cMHINFSUPP_1",
    "display" : "Geactiveerd wegens de behoefte aan ondersteuning naar aanleiding van psychische symptomen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund der Notwendigkeit nach Unterstützung aufgrund von psychischen Symptomen."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison du besoin de soutien en raison de symptômes psychologiques."
    }]
  },
  {
    "code" : "cMHINFSUPP_2",
    "display" : "Geactiveerd wegens de behoefte aan functionele ondersteuning naar aanleiding van een fysieke beperking of een cognitief onvermogen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund der Notwendigkeit nach einer funktionellen Unterstützung aufgrund einer physischen oder kognitiven Einschränkung."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison du besoin de soutien fonctionnel en raison d'une limitation physique ou d'une incapacité cognitive."
    }]
  }]
}

```
