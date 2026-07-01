# Gedrag - v0.1.0

## CodeSystem: Gedrag 

 
Gedrag 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cbehav",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cbehav",
  "version" : "0.1.0",
  "name" : "CS_cBEHAV",
  "title" : "Gedrag",
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
  "description" : "Gedrag",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cBEHAV_0",
    "display" : "Niet geactiveerd: geen gedragsproblemen (op gebied van ronddwalen, verbaal en fysiek geweld, sociaal storend gedrag, ongepast seksueel gedrag en weigeren van zorg) tijdens de laatste drie dagen.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: keine Verhaltensauffälligkeiten innerhalb der letzten drei Tage (verbale, physische Aggressionen, sozialunangepasstes Verhalten, sexuell unangepasstes Verhalten, Pflegeverweigerung)."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : pas de problème de comportement durant les 3 derniers jours (déambulation, violence verbale et physique, comportement sociale inapproprié, comportement sexuel inapproprié et résistance aux soins)."
    }]
  },
  {
    "code" : "cBEHAV_1",
    "display" : "Geactiveerd om te voorkomen dat gedragsproblemen (op gebied van ronddwalen, verbaal en fysiek geweld, sociaal storend gedrag, ongepast seksueel gedrag en weigeren van zorg) dagelijks gaan optreden.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: vermeiden von täglich auftretenden Verhaltensauffälligkeiten (verbale, physische Aggressionen, sozialunangepasstes Verhalten, sexuell unangepasstes Verhalten, Pflegeverweigerung)."
    },
    {
      "language" : "fr",
      "value" : "Activé pour prévenir chaque jour des problèmes de comportement (déambulation, violence verbale et physique, comportement sociale inapproprié, comportement sexuel inapproprié et résistance aux soins)."
    }]
  },
  {
    "code" : "cBEHAV_2",
    "display" : "Geactiveerd om dagelijkse gedragsproblemen (op gebied van ronddwalen, verbaal en fysiek geweld, sociaal storend gedrag, ongepast seksueel gedrag en weigeren van zorg te reduceren.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: Reduzierung von alltäglich auftretenden Verhaltensauffälligkeiten (verbale, physische Aggressionen, sozialunangepasstes Verhalten, sexuell unangepasstes Verhalten, Pflegeverweigerung)."
    },
    {
      "language" : "fr",
      "value" : "Activé pour réduire des problèmes quotidiens de comportement (déambulation, violence verbale et physique, comportement sociale inapproprié, comportement sexuel inapproprié et résistance aux soins)."
    }]
  }]
}

```
