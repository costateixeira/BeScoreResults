# Geneesmiddelenbeheer en therapietrouw - v0.1.0

## CodeSystem: Geneesmiddelenbeheer en therapietrouw 

 
Geneesmiddelenbeheer en therapietrouw 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhmedmgt",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhmedmgt",
  "version" : "0.1.0",
  "name" : "CS_cMHMEDMGT",
  "title" : "Geneesmiddelenbeheer en therapietrouw",
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
  "description" : "Geneesmiddelenbeheer en therapietrouw",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHMEDMGT_0",
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
    "code" : "cMHMEDMGT_1",
    "display" : "Geactiveerd wegens het vroegtijdig stoppen van geneesmiddelen ten gevolge van bijwerkingen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund eines frühzeitigen Absetzens von Medikamenten aufgrund von Nebenwirkungen."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un arrêt prématurés de médicaments suite à des effets secondaires."
    }]
  },
  {
    "code" : "cMHMEDMGT_2",
    "display" : "Geactiveerd wegens problemen met geneesmiddelenbeheer en therapietrouw in verband met cognitieve stoornissen en positieve symptomen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von Problem verbunden mit der Medikation im Zusammenhang mit kognitiven Einschränkungen und positiven Symptomen."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de problèmes liés à la gestion des médicaments et à l'observance liée aux troubles cognitifs et aux symptômes positifs."
    }]
  }]
}

```
