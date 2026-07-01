# Mantelzorg - v0.1.0

## CodeSystem: Mantelzorg 

 
Mantelzorg 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cbritsu",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cbritsu",
  "version" : "0.1.0",
  "name" : "CS_cBRITSU",
  "title" : "Mantelzorg",
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
  "description" : "Mantelzorg",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [{
    "code" : "cBRITSU_0",
    "display" : "Niet geactiveerd: afhankelijk op minstens één IADL-gebied gecombineerd met een ‘breekbaar’ informeel hulpverleningssysteem is niet van toepassing.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: Abhängigkeit in mindestens einem IADL-Bereich kombiniert mit einem ‘fragilen’ informellen Betreuungssystem ist nicht anwendbar."
    },
    {
      "language" : "fr",
      "value" : "Non activé : dépendance pour au moins un domaine-AIVQ combiné avec un système d’assistance informel « fragile » n’est pas d’application."
    }]
  },
  {
    "code" : "cBRITSU_1",
    "display" : "Geactiveerd wegens het afhankelijk zijn op minstens één IADL-gebied gecombineerd met een ‘breekbaar’ informeel hulpverleningssysteem.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: Abhängigkeit in einem IADL-Bereich kombiniert mit einem Problem der informellen Betreuungssystem."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison d'un dépendance pour un domaine-AIVQ combiné avec un problème du système d'assistance informel."
    }]
  }]
}

```
