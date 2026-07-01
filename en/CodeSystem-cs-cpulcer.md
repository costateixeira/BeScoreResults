# Decubitus - v0.1.0

## CodeSystem: Decubitus 

 
Decubitus 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cpulcer",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cpulcer",
  "version" : "0.1.0",
  "name" : "CS_cPULCER",
  "title" : "Decubitus",
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
  "description" : "Decubitus",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 4,
  "concept" : [{
    "code" : "cPULCER_0",
    "display" : "Niet geactiveerd: geen decubitus en/of risicofactoren aanwezig.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: kein Dekubitus und/oder Risiko für einen Dekubitus."
    },
    {
      "language" : "fr",
      "value" : "Non activé : pas d'escarres et/ou de facteurs de risque."
    }]
  },
  {
    "code" : "cPULCER_1",
    "display" : "Geactiveerd wegens de aanwezigheid van een decubitus stadium II of hoger waarbij genezing het zorgdoel is.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert wegen eines Dekubitus Stadium II oder mehr und bei dem es das Ziel der Pflege ist diesen zu heilen."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de présence d'une escarre de stade II ou supérieur et pour lequel la guérison est le but des soins."
    }]
  },
  {
    "code" : "cPULCER_2",
    "display" : "Geactiveerd wegens de aanwezigheid van een decubitus stadium I met risico om een decubitus stadium II of hoger te ontwikkelen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert wegen eines Dekubitus Stadium I und bei dem die Gefahr eines Dekubitus Stadium II oder mehr besteht."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de présence d'une escarre de stade I avec un risque de développer une escarre de stade II ou supérieur."
    }]
  },
  {
    "code" : "cPULCER_3",
    "display" : "Geactiveerd wegens de aanwezigheid van risicofactoren om decubitus te ontwikkelen.",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert wegen einem Risiko eines Dekubitus."
    },
    {
      "language" : "fr",
      "value" : "Activé en raison de présence de facteurs de risques de développer une escarre."
    }]
  }]
}

```
