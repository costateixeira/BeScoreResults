# BelRAI - Reden voor beoordeling - v0.1.0

## CodeSystem: BelRAI - Reden voor beoordeling 

 
Reden waarom de BelRAI beoordeling wordt uitgevoerd. 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-belrai-assessment-reason",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-belrai-assessment-reason",
  "version" : "0.1.0",
  "name" : "CS_BelRaiAssessmentReason",
  "title" : "BelRAI - Reden voor beoordeling",
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
  "description" : "Reden waarom de BelRAI beoordeling wordt uitgevoerd.",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 7,
  "concept" : [{
    "code" : "ar-first",
    "display" : "Eerste beoordeling"
  },
  {
    "code" : "ar-routine",
    "display" : "Routinematige herbeoordeling"
  },
  {
    "code" : "ar-return",
    "display" : "Terugkeerbeoordeling"
  },
  {
    "code" : "ar-condition-change",
    "display" : "Herbeoordeling wegens een significante toestandsverandering"
  },
  {
    "code" : "ar-discharge-3d",
    "display" : "Ontslagbeoordeling over de laatste 3 dagen van de zorgverlening"
  },
  {
    "code" : "ar-discharge-followup",
    "display" : "Ontslagbeoordeling enkel voor het volgen van de persoon"
  },
  {
    "code" : "ar-other",
    "display" : "Ander"
  }]
}

```
