# Mishandeling/Verwaarlozing - v0.1.0

## CodeSystem: Mishandeling/Verwaarlozing 

 
Mishandeling/Verwaarlozing 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cabuse",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cabuse",
  "version" : "0.1.0",
  "name" : "CS_cABUSE",
  "title" : "Mishandeling/Verwaarlozing",
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
  "description" : "Mishandeling/Verwaarlozing",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cABUSE_0",
    "display" : "Niet geactiveerd: geen directe indicatoren van mishandeling en stressveroorzakende factoren aanwezig.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: keine direkten Indikatoren von Misshandlungen und Stressfaktoren."
    },
    {
      "language" : "fr",
      "value" : "Non activé : pas d'indicateurs directs de maltraitance et de présence de facteurs de stress."
    }]
  },
  {
    "code" : "cABUSE_1",
    "display" : "Geactiveerd wegens matig risico: alleen directe indicatoren van mishandeling.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: wegen mittlerem Risiko von direkten Indikatoren für Misshandlungen."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un risque modéré : uniquement indicateurs direct de maltraitance."
    }]
  },
  {
    "code" : "cABUSE_2",
    "display" : "Geactiveerd wegens hoogste risico: directe indicatoren van mishandeling en stressveroorzakende factoren aanwezig (in laatste dertig dagen).",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: wegen sehr hohem Risiko von direkten Indikatoren für Misshandlungen und Stressfaktoren (innerhalb der letzten 30 Tage)."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison du risque le plus élevé : indicateurs directs de maltraitance et de présence de facteurs de stress (dans les trente derniers jours)."
    }]
  }]
}

```
