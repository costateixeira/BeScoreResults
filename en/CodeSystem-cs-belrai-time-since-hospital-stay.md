# BelRAI - Tijd sinds laatste ziekenhuisverblijf - v0.1.0

## CodeSystem: BelRAI - Tijd sinds laatste ziekenhuisverblijf 

 
Tijd verstreken sinds het meest recente ziekenhuisverblijf in de laatste 90 dagen. 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-belrai-time-since-hospital-stay",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-belrai-time-since-hospital-stay",
  "version" : "0.1.0",
  "name" : "CS_BelRaiTimeSinceHospitalStay",
  "title" : "BelRAI - Tijd sinds laatste ziekenhuisverblijf",
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
  "description" : "Tijd verstreken sinds het meest recente ziekenhuisverblijf in de laatste 90 dagen.",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 6,
  "concept" : [{
    "code" : "hs-none-90d",
    "display" : "Geen ziekenhuisopname in de laatste 90 dagen"
  },
  {
    "code" : "hs-31-90d",
    "display" : "31-90 dagen geleden"
  },
  {
    "code" : "hs-15-30d",
    "display" : "15-30 dagen geleden"
  },
  {
    "code" : "hs-8-14d",
    "display" : "8-14 dagen geleden"
  },
  {
    "code" : "hs-last-7d",
    "display" : "In de laatste 7 dagen"
  },
  {
    "code" : "hs-currently",
    "display" : "Nu in het ziekenhuis"
  }]
}

```
