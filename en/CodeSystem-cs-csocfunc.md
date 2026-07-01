# Sociale omgang - v0.1.0

## CodeSystem: Sociale omgang 

 
Sociale omgang 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-csocfunc",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-csocfunc",
  "version" : "0.1.0",
  "name" : "CS_cSOCFUNC",
  "title" : "Sociale omgang",
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
  "description" : "Sociale omgang",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cSOCFUNC_0",
    "display" : "Niet geactiveerd: normale sociale relaties of de persoon heeft geen redelijk cognitief niveau en is niet in staat anderen te begrijpen.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: normale soziale Beziehungen oder die Person hat kein rationales kognitives Niveau und ist nicht in der Lage andere zu verstehen. "
    },
    {
      "language" : "fr",
      "value" : "Non activé : relations sociales normales ou la personne n'a pas un niveau cognitif raisonnable et n'est pas en mesure à comprendre les autres."
    }]
  },
  {
    "code" : "cSOCFUNC_1",
    "display" : "Geactiveerd voor follow-up van het zorgplan: de persoon heeft een redelijk cognitief niveau en voelt zich eenzaam of verontrust.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert für eine Pflegeplanung: die Person hat ein rationales kognitives Niveau und fühlt sich einsam oder beunruhigt."
    },
    {
      "language" : "fr",
      "value" : "Activé pour le suivi du plan de soins : la personne a un niveau cognitif raisonnable et se sent solitaire ou inquiète."
    }]
  }]
}

```
