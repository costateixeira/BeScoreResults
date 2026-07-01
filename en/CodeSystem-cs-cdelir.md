# Delirium - v0.1.0

## CodeSystem: Delirium 

 
Delirium 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cdelir",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cdelir",
  "version" : "0.1.0",
  "name" : "CS_cDELIR",
  "title" : "Delirium",
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
  "description" : "Delirium",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cDELIR_0",
    "display" : "Niet geactiveerd: geen actieve deliriumsymptomen aanwezig.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: keine aktiven Deliriumsymptome."
    },
    {
      "language" : "fr",
      "value" : "Non activé : pas de symptôme de délire actif."
    }]
  },
  {
    "code" : "cDELIR_1",
    "display" : "Geactiveerd wegens actieve deliriumsymptomen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von Deliriumsymptomen."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de symptômes de délire."
    }]
  }]
}

```
