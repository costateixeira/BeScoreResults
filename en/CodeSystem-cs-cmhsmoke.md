# Roken - v0.1.0

## CodeSystem: Roken 

 
Roken 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhsmoke",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhsmoke",
  "version" : "0.1.0",
  "name" : "CS_cMHSMOKE",
  "title" : "Roken",
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
  "description" : "Roken",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHSMOKE_0",
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
    "code" : "cMHSMOKE_1",
    "display" : "Geactiveerd om het stoppen of verminderen met roken aan te moedigen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert zur Rauchentwöhnung oder Reduzierung des Rauchens."
    },
    {
      "language" : "fr",
      "value" : "Activé pour encourager le sevrage ou la réduction du tabagisme."
    }]
  },
  {
    "code" : "cMHSMOKE_2",
    "display" : "Geactiveerd voor het aanpakken van ontwenningsverschijnselen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert zur Behandlung der Entzugssymptome."
    },
    {
      "language" : "fr",
      "value" : "Activé pour traiter les symptômes de sevrage."
    }]
  }]
}

```
