# Ondersteuningskader bij ontslag - v0.1.0

## CodeSystem: Ondersteuningskader bij ontslag 

 
Ondersteuningskader bij ontslag 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhssdis",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhssdis",
  "version" : "0.1.0",
  "name" : "CS_cMHSSDIS",
  "title" : "Ondersteuningskader bij ontslag",
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
  "description" : "Ondersteuningskader bij ontslag",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cMHSSDIS_0",
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
    "code" : "cMHSSDIS_1",
    "display" : "Geactiveerd wegens de behoefte aan ondersteuning bij ontslag.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund des Bedarfs einer Begleitung nach der Entlassung."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un besoin de soutien après la sortie."
    }]
  }]
}

```
