# Fysieke fixatie - v0.1.0

## CodeSystem: Fysieke fixatie 

 
Fysieke fixatie 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-crestr",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-crestr",
  "version" : "0.1.0",
  "name" : "CS_cRESTR",
  "title" : "Fysieke fixatie",
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
  "description" : "Fysieke fixatie",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cRESTR_0",
    "display" : "Niet geactiveerd: de bewegingsvrijheid van de persoon wordt niet beperkt door fixatiemateriaal.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: Die Bewegungsfreiheit der Person ist nicht durch freiheitsbeschränkende Maßnahmen eingeschränkt."
    },
    {
      "language" : "fr",
      "value" : "Non activé : la liberté de mouvement de la personne n'est pas limitée par du matériel de contention."
    }]
  },
  {
    "code" : "cRESTR_1",
    "display" : "Geactiveerd om fixatiemateriaal te verwijderen waarbij de persoon zelf (bijna) niet meer in staat is ‘middle loss’ of ‘early loss’ ADL-activiteiten uit te voeren.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um eine freiheitsbeschränkende Maßnahme aufzuheben, wobei die Person nicht mehr oder kaum in der Lage ist ADLs auszuführen."
    },
    {
      "language" : "fr",
      "value" : "Activé pour enlever une restriction physique chez une personne ne disposant presque plus d’une aptitude moyenne ou récemment amoindrie pour l’accomplissement des AVQ."
    }]
  },
  {
    "code" : "cRESTR_2",
    "display" : "Geactiveerd om fixatiemateriaal te verwijderen waarbij de persoon zelf nog enkele ‘middle loss’ of ‘early loss’ ADL-activiteiten kan uitvoeren.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um eine freiheitsbeschränkende Maßnahme aufzuheben, wobei die Person kaum oder teilweise noch in der Lage ist ADLs auszuführen."
    },
    {
      "language" : "fr",
      "value" : "Activé pour enlever une restriction physique chez une personne disposant encore d’une aptitude moyenne ou récemment amoindrie pour l’accomplissement des AVQ."
    }]
  }]
}

```
