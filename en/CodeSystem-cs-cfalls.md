# Valincidenten - v0.1.0

## CodeSystem: Valincidenten 

 
Valincidenten 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cfalls",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cfalls",
  "version" : "0.1.0",
  "name" : "CS_cFALLS",
  "title" : "Valincidenten",
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
  "description" : "Valincidenten",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cFALLS_0",
    "display" : "Niet geactiveerd: geen valincidenten in de laatste 90 dagen.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: kein Sturz in den letzten 90 Tagen."
    },
    {
      "language" : "fr",
      "value" : "Non activé : pas de chute dans les 90 derniers jours."
    }]
  },
  {
    "code" : "cFALLS_1",
    "display" : "Geactiveerd wegens een gemiddeld risico op valincidenten, gebaseerd op één gerapporteerd valincident in de laatste 90 dagen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: mittleres Sturzrisiko, aufgrund eines Sturzes innerhalb der letzten 90 Tage."
    },
    {
      "language" : "fr",
      "value" : "Activé pour cause d'un risque moyen de chutes, basé sur un incident de chute rapporté dans les 90 derniers jours."
    }]
  },
  {
    "code" : "cFALLS_2",
    "display" : "Geactiveerd wegens een hoog risico op valincidenten, gebaseerd op veel gerapporteerde valincidenten in de laatste 30 dagen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: hohes Sturzrisiko, aufgrund mehrerer Stürze innerhalb der letzten 30 Tage."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque élevé de chutes, basé sur beaucoup de chutes rapportées dans les 30 derniers jours."
    }]
  }]
}

```
