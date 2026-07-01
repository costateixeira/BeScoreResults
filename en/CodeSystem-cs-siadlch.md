# IADL Capacity Hierarchy Scale (sIADLCH) - v0.1.0

## CodeSystem: IADL Capacity Hierarchy Scale (sIADLCH) 

 
IADL Capacity Hierarchy Scale (sIADLCH) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-siadlch",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-siadlch",
  "version" : "0.1.0",
  "name" : "CS_sIADLCH",
  "title" : "IADL Capacity Hierarchy Scale (sIADLCH)",
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
  "description" : "IADL Capacity Hierarchy Scale (sIADLCH)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 7,
  "concept" : [{
    "code" : "sIADLCH_0",
    "display" : "Geen problemen",
    "designation" : [{
      "language" : "de",
      "value" : "Keine Probleme"
    },
    {
      "language" : "fr",
      "value" : "Pas de problème"
    }]
  },
  {
    "code" : "sIADLCH_1",
    "display" : "Een enkel probleem",
    "designation" : [{
      "language" : "de",
      "value" : "Ein einziges Problem"
    },
    {
      "language" : "fr",
      "value" : "Un seul problème "
    }]
  },
  {
    "code" : "sIADLCH_2",
    "display" : "Twee of drie problemen",
    "designation" : [{
      "language" : "de",
      "value" : "2 oder 3 Probleme"
    },
    {
      "language" : "fr",
      "value" : "2 ou 3 problèmes"
    }]
  },
  {
    "code" : "sIADLCH_3",
    "display" : "Vier of meer problemen",
    "designation" : [{
      "language" : "de",
      "value" : "4 oder mehr Probleme"
    },
    {
      "language" : "fr",
      "value" : "4 ou plus de 4 problèmes"
    }]
  },
  {
    "code" : "sIADLCH_4",
    "display" : "Soms afhankelijk",
    "designation" : [{
      "language" : "de",
      "value" : "Manchmal abhängig"
    },
    {
      "language" : "fr",
      "value" : "Parfois dépendant"
    }]
  },
  {
    "code" : "sIADLCH_5",
    "display" : "Meestal afhankelijk",
    "designation" : [{
      "language" : "de",
      "value" : "Meistens abhängig"
    },
    {
      "language" : "fr",
      "value" : "Souvent dépendant"
    }]
  },
  {
    "code" : "sIADLCH_6",
    "display" : "Altijd afhankelijk",
    "designation" : [{
      "language" : "de",
      "value" : "Immer abhängig"
    },
    {
      "language" : "fr",
      "value" : "Toujours dépendant"
    }]
  }]
}

```
