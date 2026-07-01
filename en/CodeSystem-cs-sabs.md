# Aggressive Behaviour Scale (sABS) - v0.1.0

## CodeSystem: Aggressive Behaviour Scale (sABS) 

 
Aggressive Behaviour Scale (sABS) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-sabs",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-sabs",
  "version" : "0.1.0",
  "name" : "CS_sABS",
  "title" : "Aggressive Behaviour Scale (sABS)",
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
  "description" : "Aggressive Behaviour Scale (sABS)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "sABS_0",
    "display" : "Geen tekenen van agressie",
    "designation" : [{
      "language" : "de",
      "value" : "Keine Anzeichen von Aggressionen"
    },
    {
      "language" : "fr",
      "value" : "Pas de signe d'agression"
    }]
  },
  {
    "code" : "sABS_range_1_4",
    "display" : "1-4 Lichte tot matige agressie",
    "designation" : [{
      "language" : "de",
      "value" : "1-4 Leichte oder moderate Aggressionen"
    },
    {
      "language" : "fr",
      "value" : "1-4 Agression légère ou modérée"
    }]
  },
  {
    "code" : "sABS_range_5_12",
    "display" : "5-12 Ernstige agressie",
    "designation" : [{
      "language" : "de",
      "value" : "5-12 Ernste Aggressionen"
    },
    {
      "language" : "fr",
      "value" : "5-12 Agression sérieuse"
    }]
  }]
}

```
