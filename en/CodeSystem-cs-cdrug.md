# Juist en verantwoord medicatiegebruik - v0.1.0

## CodeSystem: Juist en verantwoord medicatiegebruik 

 
Juist en verantwoord medicatiegebruik 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cdrug",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cdrug",
  "version" : "0.1.0",
  "name" : "CS_cDRUG",
  "title" : "Juist en verantwoord medicatiegebruik",
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
  "description" : "Juist en verantwoord medicatiegebruik",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cDRUG_0",
    "display" : "Niet geactiveerd: medicatiereview is op dit moment geen prioriteit.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: die Überprüfung der Medikation hat im Moment keine Priorität."
    },
    {
      "language" : "fr",
      "value" : "Non activé : la révision des médicaments n'est pas une priorité pour le moment."
    }]
  },
  {
    "code" : "cDRUG_1",
    "display" : "Geactiveerd wegens hoge prioriteit: meer dan negen verschillende geneesmiddelen gecombineerd met een onstabiele gezondheid.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert aufgrund von hohem Risiko: Kombination von mehr als neun verschiedenen Medikamenten mit einem instabilen Gesundheitszustand."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'une priorité élevée : combinaison de plus de neuf médicaments différents avec une santé instable."
    }]
  }]
}

```
