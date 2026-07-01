# Sondevoeding - v0.1.0

## CodeSystem: Sondevoeding 

 
Sondevoeding 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cfeedtb",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cfeedtb",
  "version" : "0.1.0",
  "name" : "CS_cFEEDTB",
  "title" : "Sondevoeding",
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
  "description" : "Sondevoeding",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cFEEDTB_0",
    "display" : "Niet geactiveerd.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert."
    },
    {
      "language" : "fr",
      "value" : "Non activé."
    }]
  },
  {
    "code" : "cFEEDTB_1",
    "display" : "Geactiveerd wegens laag risico: de persoon heeft geen cognitieve capaciteiten meer.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von leichtem Risiko: die Person hat keine kognitiven Fähigkeiten mehr."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un faible risque : la personne n'a plus de capacités cognitives."
    }]
  },
  {
    "code" : "cFEEDTB_2",
    "display" : "Geactiveerd wegens hoog risico: de persoon heeft nog enkele cognitieve capaciteiten.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von hohem Risiko: die Person hat noch einige kognitive Fähigkeiten."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque élevé : la personne a encore quelques capacités cognitives."
    }]
  }]
}

```
