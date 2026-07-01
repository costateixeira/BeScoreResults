# Beweging - v0.1.0

## CodeSystem: Beweging 

 
Beweging 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cmhexer",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cmhexer",
  "version" : "0.1.0",
  "name" : "CS_cMHEXER",
  "title" : "Beweging",
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
  "description" : "Beweging",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cMHEXER_0",
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
    "code" : "cMHEXER_1",
    "display" : "Geactiveerd om de fysieke activiteit te verhogen, maar met nood aan extra aandacht wegens een medische aandoening.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um die physische Aktivität zu steigern, aufgrund einer Erkrankung jedoch eine zusätzliche Beobachtung benötigt."
    },
    {
      "language" : "fr",
      "value" : "Activé pour augmenter l'activité physique, mais nécessitant une attention particulière en raison d'une maladie."
    }]
  },
  {
    "code" : "cMHEXER_2",
    "display" : "Geactiveerd om de fysieke activiteit te verhogen bij personen die tot fysieke activiteit in staat zijn.",
    "designation" : [{
      "language" : "de",
      "value" : " Aktiviert um die physische Aktivität zu steigern bei Personen die dazu in der Lage sind;"
    },
    {
      "language" : "fr",
      "value" : "Activé pour augmenter l'activité physique chez les personnes capables d'activité physique."
    }]
  }]
}

```
