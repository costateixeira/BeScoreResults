# Kans op opname in een voorziening - Ziekenhuis - v0.1.0

## CodeSystem: Kans op opname in een voorziening - Ziekenhuis 

 
Kans op opname in een voorziening - Ziekenhuis 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-chsinstitution",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-chsinstitution",
  "version" : "0.1.0",
  "name" : "CS_cHSINSTITUTION",
  "title" : "Kans op opname in een voorziening - Ziekenhuis",
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
  "description" : "Kans op opname in een voorziening - Ziekenhuis",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 4,
  "concept" : [{
    "code" : "cHSINSTITUTION_0",
    "display" : "Niet geactiveerd",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert"
    },
    {
      "language" : "fr",
      "value" : "Non activé"
    }]
  },
  {
    "code" : "cHSINSTITUTION_1",
    "display" : "Matig risico",
    "designation" : [{
      "language" : "de",
      "value" : "Moderates Risiko"
    },
    {
      "language" : "fr",
      "value" : "Risque modéré"
    }]
  },
  {
    "code" : "cHSINSTITUTION_2",
    "display" : "Hoog risico",
    "designation" : [{
      "language" : "de",
      "value" : "Hohes Risiko"
    },
    {
      "language" : "fr",
      "value" : "Risque élevé"
    }]
  },
  {
    "code" : "cHSINSTITUTION_8",
    "display" : "In voorziening vóór de opname",
    "designation" : [{
      "language" : "de",
      "value" : "In der Einrichtung vor der Aufnahme"
    },
    {
      "language" : "fr",
      "value" : "Dans l'institution avant l'admission"
    }]
  }]
}

```
