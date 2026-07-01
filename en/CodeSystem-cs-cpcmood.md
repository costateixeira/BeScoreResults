# Stemming-Palliative Care - v0.1.0

## CodeSystem: Stemming-Palliative Care 

 
Stemming-Palliative Care 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cpcmood",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cpcmood",
  "version" : "0.1.0",
  "name" : "CS_cPCMOOD",
  "title" : "Stemming-Palliative Care",
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
  "description" : "Stemming-Palliative Care",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cPCMOOD_0",
    "display" : "Niet geactiveerd: er zijn geen symptomen van stemmingsstoornissen aanwezig.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: Es treten keine Symptome einer affektiven Störung auf."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : il n'y a pas de présence de symptômes de troubles de l'humeur."
    }]
  },
  {
    "code" : "cPCMOOD_1",
    "display" : "Geactiveerd: slechts 1 symptoom van stemmingsstoornissen aanwezig.",
    "designation" : [{
      "language" : "de",
      "value" : " Aktiviert: Es tritt ein einziges Symptome einer affektiven Störung auf."
    },
    {
      "language" : "fr",
      "value" : "Activé : présence seulement d'1 symptôme de troubles de l'humeur."
    }]
  },
  {
    "code" : "cPCMOOD_2",
    "display" : "Geactiveerd: meerdere symptomen van stemmingsstoornissen aanwezig.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: Es treten mehrere Symptome einer affektiven Störung auf."
    },
    {
      "language" : "fr",
      "value" : "Activé : présence de plusieurs symptômes de troubles de l'humeur."
    }]
  }]
}

```
