# Dehydratatie - v0.1.0

## CodeSystem: Dehydratatie 

 
Dehydratatie 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cdehyd",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cdehyd",
  "version" : "0.1.0",
  "name" : "CS_cDEHYD",
  "title" : "Dehydratatie",
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
  "description" : "Dehydratatie",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cDEHYD_0",
    "display" : "Niet geactiveerd: geen verstoorde vochtbalans en/of dehydratatie.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: kein beeinträchtigter Flüssigkeitshaushalt und oder Dehydratation."
    },
    {
      "language" : "fr",
      "value" : "Non activé : pas d'équilibre des fluides altéré et/ou de déshydratation."
    }]
  },
  {
    "code" : "cDEHYD_1",
    "display" : "Geactiveerd wegens laag niveau: geen complicaties van dehydratatie.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von leichtem Risiko: keine Probleme mit Dehydratation."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un niveau faible : pas de complications de déshydratation."
    }]
  },
  {
    "code" : "cDEHYD_2",
    "display" : "Geactiveerd wegens hoog niveau: met oorzaken of complicaties van dehydratatie.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von hohem Risiko: Komplikationen mit Dehydratation."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un niveau élevé : complications de déshydratation."
    }]
  }]
}

```
