# Pijn - Mentale gezondheid - v0.1.0

## CodeSystem: Pijn - Mentale gezondheid 

 
Pijn - Mentale gezondheid 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhpain",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhpain",
  "version" : "0.1.0",
  "name" : "CS_cMHPAIN",
  "title" : "Pijn - Mentale gezondheid",
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
  "description" : "Pijn - Mentale gezondheid",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHPAIN_0",
    "display" : "Niet geactiveerd:  geen pijn of minder dan dagelijks milde tot matige pijn.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: keine Schmerzen oder weniger als leichte und moderate tägliche Schmerzen."
    },
    {
      "language" : "fr",
      "value" : "Pas activité : pas de douleur ou moins que la douleur quotidienne légère à modérée."
    }]
  },
  {
    "code" : "cMHPAIN_1",
    "display" : "Geactiveerd met middelhoge prioriteit: dagelijkse pijn die omschreven wordt als mild of matig.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert mit mittlerer Priorität: tägliche Schmerzen, die als leicht oder moderat beschrieben werden."
    },
    {
      "language" : "fr",
      "value" : "Activé avec une priorité moyenne : douleur quotidienne qui est décrite comme légère ou modérée."
    }]
  },
  {
    "code" : "cMHPAIN_2",
    "display" : "Geactiveerd met hoge prioriteit: pijn die omschreven wordt als ernstig, afschuwelijk of ondraaglijk (ongeacht of de pijn dagelijks of minder vaak voorkomt).",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert mit hoher Priorität: Schmerzen, die als ernst, schrecklich und unerträglich beschrieben werden (unabhängig davon ob der Schmerz täglich oder weniger häufig auftritt)."
    },
    {
      "language" : "fr",
      "value" : "Activé avec une priorité élevée : douleur qui est décrite comme sérieux, horrible ou intolérable (que la douleur se produise tous les jours ou moins souvent)."
    }]
  }]
}

```
