# Pijn - Palliatieve zorg - v0.1.0

## CodeSystem: Pijn - Palliatieve zorg 

 
Pijn - Palliatieve zorg 

This Code system is referenced in the definition of the following value sets:

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-cpcpain",
  "url" : "https://www.ehealth.fgov.be/standards/fhir/scoring/CodeSystem/cs-cpcpain",
  "version" : "0.1.0",
  "name" : "CS_cPCPAIN",
  "title" : "Pijn - Palliatieve zorg",
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
  "description" : "Pijn - Palliatieve zorg",
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 3,
  "concept" : [{
    "code" : "cPCPAIN_0",
    "display" : "Niet geactiveerd: de persoon ervaart geen of matige pijn zonder doorbraakpijn.",
    "designation" : [{
      "language" : "de",
      "value" : "Nicht aktiviert: die Person erlebt keine oder moderater Schmerzen ohne paroxysmale Schmerzen."
    },
    {
      "language" : "fr",
      "value" : "Pas activé : la personne n'éprouve pas de douleur modérée ou une douleur modérée sans douleur paroxystique."
    }]
  },
  {
    "code" : "cPCPAIN_1",
    "display" : "Geactiveerd: de persoon ervaart milde of matige pijn en doorbraakpijn (Pijnschaal code 2).",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: die Person erlebt leichte oder moderate Schmerzen und paroxysmale Schmerzen."
    },
    {
      "language" : "fr",
      "value" : "Activé : la personne éprouve une douleur légère ou modérée et des douleurs paroxystiques."
    }]
  },
  {
    "code" : "cPCPAIN_2",
    "display" : "Geactiveerd: de persoon ervaart ernstige of intense pijn en de pijn is al of niet constant aanwezig (Pijnschaal code 3 en 4).",
    "designation" : [{
      "language" : "de",
      "value" : "Aktiviert: die Person erlebt starke oder intensive Schmerzen und die Schmerzen sind nicht konstant anwesend (Schmerzskala 3 oder 4)."
    },
    {
      "language" : "fr",
      "value" : "Activé : la personne éprouve une douleur sévère ou intense et la douleur n'est pas présente de façon constante (échelle de douleur code 3 ou 4)."
    }]
  }]
}

```
