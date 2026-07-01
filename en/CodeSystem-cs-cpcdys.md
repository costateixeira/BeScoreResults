# Dyspneu - v0.1.0

## CodeSystem: Dyspneu 

 
Dyspneu 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cpcdys",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cpcdys",
  "version" : "0.1.0",
  "name" : "CS_cPCDYS",
  "title" : "Dyspneu",
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
  "description" : "Dyspneu",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cPCDYS_0",
    "display" : "Niet geactiveerd: geen dyspneu of geen dyspneu in rust maar wel tijdens zware activiteiten.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: Keine Dyspnoe oder keine Dyspnoe im Ruhezustand, wohl aber während anstrengenden Aktivitäten."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : pas de dyspnée ou pas de dyspnée au repos mais bien durant des activités lourdes."
    }]
  },
  {
    "code" : "cPCDYS_1",
    "display" : "Geactiveerd: dyspneu  in rust of geen dyspneu in rust maar wel tijdens normale dagelijkse activiteiten.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: Keine Dyspnoe oder Dyspnoe im Ruhezustand, wohl aber während normalen alltäglichen Aktivitäten. "
    },
    {
      "language" : "fr",
      "value" : "Activé : dyspnées au repos ou pas de dyspnée au repos mais bien durant des activités quotidiennes normales."
    }]
  }]
}

```
