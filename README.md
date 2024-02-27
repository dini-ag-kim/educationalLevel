# Werteliste für Bildungsstufen
Werteliste der Bildungsstufen in der deutschen Bildungslandschaft, gepflegt von der [OER-Metadatengruppe](https://wiki.dnb.de/x/IQ30B) und der [Curricula-Gruppe](https://wiki.dnb.de/display/DINIAGKIM/Curricula-Gruppe) der DINI-AG-KIM. Die Bildungsstufe verortet das zu beschreibende Objekt (z. B. eine Ressource, eine Zielgruppe) in einen Lehr-/Lernkontext im [deutschen Bildungssystem](https://www.bpb.de/themen/bildung/dossier-bildung/163283/das-bildungssystem-in-deutschland/). So könnte die Bildungsstufe beispielsweise den Zeitpunkt in der sukzessiven Ausbildung eines Lernenden beschreiben oder den ausgewiesenen Einsatzort einer Ressource

## Verwendung als Metadaten

### Vorgesehene Felder
- [schema.org:educationalLevel](https://schema.org/educationalLevel)

### Verwandte Felder in Applikationsprofilen

- [AMB:educationalLevel (4.29)](https://w3id.org/kim/amb/draft/#educationallevel)
- [LOM-CH v2.1:Bildungsstufe (5.6)](https://www.educa.ch/sites/default/files/2020-11/applikationsprofil-lom-ch-v2.1-de.pdf)
- [LOM-DE v0.9:Educational.Context (5.6)](https://web.archive.org/web/20220120213540/https://sodis.de/lom-de/LOM-DE_v0.9_1.pdf)

## Maintainer\*innen
- [Steffen Rörtgen](https://github.com/sroertgen)
- [Manuel Oellers](https://github.com/oellers)

## Status
|Version| Veröffentlichung |
|--|--|
| 1.0 | 02.05.2022 |

## Mitarbeit und Kontakt
Mitarbeit und Kontakt über [Issues](https://github.com/dini-ag-kim/educationalLevel/issues/), die [Mailingliste der OER-Metadatengruppe](https://lists.dnb.de/mailman/listinfo/dini-ag-kim-oer) oder die [Mailingliste der Curricula-Gruppe](https://lists.dnb.de/mailman/listinfo/dini-ag-kim-curricula).

## Entwicklung und Publikation
In der Entwicklung des Vokabulars nutzen wir die [StöberSpecs](https://w3id.org/kim/stoeberspecs/)-Werkzeuge und -Prozesse. Das Vokabular wird in diesem [GitHub Repo](https://github.com/dini-ag-kim/educationalLevel) in der Datei [educationalLevel.ttl](https://github.com/dini-ag-kim/educationalLevel/blob/master/educationalLevel.ttl) versioniert und gepflegt. Als Beschreibungssprache wird das [Simple Knowledge Organization System (SKOS)](https://www.w3.org/2004/02/skos/) in [Turtle](https://www.w3.org/TR/turtle/)-Syntax verwendet.

### Entstehungshintergrund
Diese Werteliste ist eine Synthese aus verschiedenen Wertelisten, die für Bildungsressourcen verwendet werden.
| Bildungsstufen (diese Liste) |  [WLO-educationalContext](http://w3id.org/openeduhub/vocabs/educationalContext/) | [ComeIn-educationalLevel](http://w3id.org/comein/vocabs/educationalLevel-ComeIn/) | [ISCED-P & ISCED-A](http://uis.unesco.org/sites/default/files/documents/international-standard-classification-of-education-isced-2011-en.pdf) | [LOM-CH v2.1-educational level](https://www.educa.ch/sites/default/files/2020-11/applikationsprofil-lom-ch-v2.1-de.pdf) | [WLO-educationalLevel](http://w3id.org/openeduhub/vocabs/educationalLevel/) | [SODIS](http://cp.sodis.de/api/get?lom_context=*) |
| -------- | -------- | -------- | -------- | -------- |-------- | -------- |
| Elementarbereich  | Elementarbereich     |  Elementarbereich | 0 |  Frühbereich |   | Elementarbildung  |
| Primarbereich  | Primarstufe      | Primarbereich | 1 |  Obligatorische Schule | 1 - 4 | Allgemeinbildende Schule; Grundschule   |
| Sekundarstufe I  | Sekundarstufe I      | Sekundarbereich I | 2 |   Obligatorische Schule | 5 - 10 |  Allgemeinbildende Schule; Sekundarstufe I |
| Sekundarstufe II  | Sekundarstufe II     | Sekundarbereich II | 3   |  Sekundarstufe II | 11 - 13 | Allgemeinbildende Schule; Sekundarstufe II   |
| Hochschule | Hochschule     | Hochschule | 6,7,8 |  Tertiärstufe  | |  Hochschule |
| Hochschule > Bachelor | Hochschule  | Hochschule > Bachelor | 6|  Tertiärstufe  |  |   |
| Hochschule > Master  | Hochschule | Hochschule > Master |  7 | Tertiärstufe |  |   |
| Hochschule > Promotion | Hochschule | Hochschule > Promotion |  8 | Tertiärstufe |  |   |
| Postsekundarer nicht-tertiärer Bereich | Berufliche Bildung     |  Berufliche Bildung | 4 |  Tertiärstufe   |  | Berufliche Bildung  |
| Kurzes tertiäres Bildungsprogramm | | | 5 | | |    |
| Fortbildung | Fortbildung     | Fortbildung |  |  |  | Fortbildung  |
| | | |  | Weiterbildung |  |    |
| Vorbereitungsdienst | | Vorbereitungsdienst|   |  | |   |
| | Erwachsenenbildung     |  |  | |  |  Erwachsenenbildung |
| | Förderschule     | |  |  | |   |
| | ||  | Sonderpädagogik |  |  Sonderpädagogische Förderung  |
| | Fernunterricht     | |  | Fernunterricht |     | Fernunterricht |
| | ||  | Stufenunabhängig |  |    |
| | | | 9 | Nicht definiert | | anderer Bereich   |
| | | |  |  | | Bibliothek   |
| | | |  |  | | Schulverwaltung   |
| | | |  |  | | Schulpolitik   |


