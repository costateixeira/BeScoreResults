# ADL Hierarchy Scale (sADLH) - v0.1.0

## CodeSystem: ADL Hierarchy Scale (sADLH) 

 
ADL Hierarchy Scale (sADLH) 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-sadlh",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-sadlh",
  "version" : "0.1.0",
  "name" : "CS_sADLH",
  "title" : "ADL Hierarchy Scale (sADLH)",
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
  "description" : "ADL Hierarchy Scale (sADLH)",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 7,
  "concept" : [{
    "code" : "sADLH_0",
    "display" : "Zelfstandig bij de 4 ADL-functies.",
    "designation" : [{
      "language" : "de",
      "value" : "Selbständig für die 4 ADL-Funktionen."
    },
    {
      "language" : "fr",
      "value" : "Indépendant pour les 4 fonctions AVQ."
    }]
  },
  {
    "code" : "sADLH_1",
    "display" : "Tenminste toezicht bij één ADL-functie (en minder dan beperkte hulp bij alle 4 ADL-functies).",
    "designation" : [{
      "language" : "de",
      "value" : "Begleitung bei mindestens einer ADL-Funktion (und mindestens eine leichte Unterstützung bei den 4 ADL-Funktionen)."
    },
    {
      "language" : "fr",
      "value" : "Supervision d'au moins une fonction AVQ (et moins qu’une assistance limitée pour les 4 fonctions AVQ)."
    }]
  },
  {
    "code" : "sADLH_2",
    "display" : "Beperkte hulp vereist bij 1 of meer van de 4 ADL-functies (en minder dan uitgebreide hulp bij alle 4 ADL-functies).",
    "designation" : [{
      "language" : "de",
      "value" : "Leichte Unterstützung bei mindestens einer ADL-Funktion (und mindestens eine erweiterte Unterstützung bei den 4 ADL-Funktionen)."
    },
    {
      "language" : "fr",
      "value" : "Assistance limitée exigée pour minimum une des 4 fonctions AVQ (et moins qu’une assistance étendue pour les toutes les 4 fonctions AVQ)."
    }]
  },
  {
    "code" : "sADLH_3",
    "display" : "Tenminste uitgebreide hulp vereist bij de persoonlijke hygiëne en/of het toiletgebruik (en minder dan uitgebreide hulp vereist bij het eten en het zich verplaatsen).",
    "designation" : [{
      "language" : "de",
      "value" : "Unterstützung mindestens bei der Körpertoilette und/oder dem Toilettengang (und mindestens eine erweiterte Unterstützung zur Nahrungsaufnahme und Fortbewegung)."
    },
    {
      "language" : "fr",
      "value" : "Au moins une assistance importante exigée pour l’hygiène personnelle et/ou l’utilisation des toilettes (et moins qu’une assistance étendue exigée pour l’alimentation et le déplacement)."
    }]
  },
  {
    "code" : "sADLH_4",
    "display" : "Uitgebreide hulp vereist bij het eten en/of het zich verplaatsen (geen totale afhankelijkheid bij het eten en het zich verplaatsen).",
    "designation" : [{
      "language" : "de",
      "value" : "Unterstützung mindestens bei der Nahrungsaufnahme und/oder der Fortbewegung (keine vollständige Unterstützung zur Nahrungsaufnahme und/oder Fortbewegung)."
    },
    {
      "language" : "fr",
      "value" : "Assistance importante exigée pour l’alimentation et/ou le déplacement (pas de dépendance totale pour l’alimentation et/ou pour le déplacement)."
    }]
  },
  {
    "code" : "sADLH_5",
    "display" : "Totale afhankelijkheid bij het eten en/of het zich verplaatsen.",
    "designation" : [{
      "language" : "de",
      "value" : "Vollständige Abhängigkeit bei der Nahrungsaufnahme und/oder der Fortbewegung."
    },
    {
      "language" : "fr",
      "value" : "Dépendance totale pour l’alimentation et/ou pour le déplacement."
    }]
  },
  {
    "code" : "sADLH_6",
    "display" : "Totale afhankelijkheid bij de 4 ADL-functies.",
    "designation" : [{
      "language" : "de",
      "value" : "Vollständige Abhängigkeit für die 4 ADL-Funktionen."
    },
    {
      "language" : "fr",
      "value" : "Dépendance totale pour les 4 fonctions AVQ."
    }]
  }]
}

```
