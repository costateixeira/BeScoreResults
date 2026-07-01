# BelRAI - Relatiestatus - v0.1.0

## CodeSystem: BelRAI - Relatiestatus 

 
Relatiestatus van de persoon. 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-belrai-marital-status",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-belrai-marital-status",
  "version" : "0.1.0",
  "name" : "CS_BelRaiMaritalStatus",
  "title" : "BelRAI - Relatiestatus",
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
  "description" : "Relatiestatus van de persoon.",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 6,
  "concept" : [{
    "code" : "mar-never-married",
    "display" : "Nooit gehuwd/geen geregistreerd partnerschap"
  },
  {
    "code" : "mar-married",
    "display" : "Gehuwd/ander geregistreerd partnerschap"
  },
  {
    "code" : "mar-cohabiting",
    "display" : "Samenwonend met partner"
  },
  {
    "code" : "mar-widowed",
    "display" : "Weduwe/weduwnaar"
  },
  {
    "code" : "mar-de-facto-separated",
    "display" : "Feitelijk gescheiden"
  },
  {
    "code" : "mar-legally-separated",
    "display" : "Wettelijk gescheiden"
  }]
}

```
