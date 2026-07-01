# Doorverwijzing naar de tandarts - v0.1.0

## CodeSystem: Doorverwijzing naar de tandarts 

 
Doorverwijzing naar de tandarts 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cdentistrefer",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cdentistrefer",
  "version" : "0.1.0",
  "name" : "CS_cDENTISTREFER",
  "title" : "Doorverwijzing naar de tandarts",
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
  "description" : "Doorverwijzing naar de tandarts",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cDENTISTREFER_0",
    "display" : "Niet geactiveerd, doorverwijzing naar een tandarts is momenteel geen prioriteit.\n",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert,der Besuch eines Zahnarztes hat deerzeit keine Priorität\n"
    },
    {
      "language" : "fr",
      "value" : "Non activé, la consultation d'un dentiste n'est pas une priorité actuellement.\n"
    }]
  },
  {
    "code" : "cDENTISTREFER_1",
    "display" : "Geactiveerd, doorverwijzing naar een tandarts is aangewezen.\n",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert, Zahnarztbesuch wird empfohlen\n"
    },
    {
      "language" : "fr",
      "value" : "Activé, la consultation d'un dentiste est conseillée\n"
    }]
  }]
}

```
