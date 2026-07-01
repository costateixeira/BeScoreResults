# Deafblind Severity Index (sDbSI) - v0.1.0

## CodeSystem: Deafblind Severity Index (sDbSI) 

 
Deafblind Severity Index (sDbSI) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-sdbsi",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-sdbsi",
  "version" : "0.1.0",
  "name" : "CS_sDbSI",
  "title" : "Deafblind Severity Index (sDbSI)",
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
  "description" : "Deafblind Severity Index (sDbSI)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 6,
  "concept" : [{
    "code" : "sDbSI_0",
    "display" : "Beide zintuigen zijn intact.",
    "designation" : [{
      "language" : "de",
      "value" : "Beide Sinne sind intakt."
    },
    {
      "language" : "fr",
      "value" : "Les 2 sens sont intacts."
    }]
  },
  {
    "code" : "sDbSI_1",
    "display" : "Eén zintuig is intact en het andere zintuig is licht tot matig verstoord.",
    "designation" : [{
      "language" : "de",
      "value" : "Ein Sinn ist intakt ein anderer Sinn ist leicht oder moderat beeinträchtigt."
    },
    {
      "language" : "fr",
      "value" : "Un sens est intact et l'autre sens légèrement ou modérément perturbé."
    }]
  },
  {
    "code" : "sDbSI_2",
    "display" : "Eén zintuig is intact en het andere zintuig is ernstig verstoord.",
    "designation" : [{
      "language" : "de",
      "value" : "Ein Sinn ist intakt ein anderer Sinn ist ernsthaft beeinträchtigt."
    },
    {
      "language" : "fr",
      "value" : "Un sens est intact et l'autre sens est sévèrement perturbé."
    }]
  },
  {
    "code" : "sDbSI_3",
    "display" : "Beide zintuigen zijn licht tot matig verstoord.",
    "designation" : [{
      "language" : "de",
      "value" : "Beide Sinne sind leicht oder moderat beeinträchtigt."
    },
    {
      "language" : "fr",
      "value" : "Les 2 sens sont légèrement ou modérément perturbés."
    }]
  },
  {
    "code" : "sDbSI_4",
    "display" : "Eén zintuig is licht tot matig verstoord en het andere zintuig is ernstig verstoord.",
    "designation" : [{
      "language" : "de",
      "value" : "Ein Sinn ist leicht oder moderat beeinträchtigt und ein anderer Sinn ist ernsthaft beeinträchtigt."
    },
    {
      "language" : "fr",
      "value" : "Un sens est légèrement ou modérément perturbé et l'autre sens est sévèrement perturbé."
    }]
  },
  {
    "code" : "sDbSI_5",
    "display" : "Beide zintuigen zijn ernstig verstoord.",
    "designation" : [{
      "language" : "de",
      "value" : "Beide Sinne sind ernsthaft beeinträchtigt."
    },
    {
      "language" : "fr",
      "value" : "Les 2 sens sont sévèrement perturbé."
    }]
  }]
}

```
