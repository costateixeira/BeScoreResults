# Mondhygiëne - v0.1.0

## CodeSystem: Mondhygiëne 

 
Mondhygiëne 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-coralhyg",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-coralhyg",
  "version" : "0.1.0",
  "name" : "CS_cORALHYG",
  "title" : "Mondhygiëne",
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
  "description" : "Mondhygiëne",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cORALHYG_0",
    "display" : "Niet geactiveerd, geen plaque en tandsteen zichtbaar.\n",
    "designation" : [{
      "language" : "de",
      "value" : " Nicht aktiviert, keine sichtbaren Plaque-oder Kalkablagerungen\n"
    },
    {
      "language" : "fr",
      "value" : "Non activé, pas de plaque ni de tartre visibles.\n"
    }]
  },
  {
    "code" : "cORALHYG_1",
    "display" : "Geactiveerd om dagelijkse mondhygiëne te verbeteren.\n",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert um die tägliche Mundhygiene zu verbessern\n"
    },
    {
      "language" : "fr",
      "value" : "Activé pour améliorer l'hygiène bucco-dentaire quotidienne. \n"
    }]
  }]
}

```
