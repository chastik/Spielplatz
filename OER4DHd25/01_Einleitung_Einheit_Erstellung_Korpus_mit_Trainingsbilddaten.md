<!--

author: Mathias Zinnen und Canan Hastik  
email:    
version:  v1
language: DE

icon:     https://raw.githubusercontent.com/chastik/Beratung_Dateityp_Bild/refs/heads/main/SODa-Logo_full.svg
link:     https://raw.githubusercontent.com/chastik/Beratung/refs/heads/main/soda.css

comment:  WissKi SODA OERs

-->

# Willkommen zu SODa OERs (Semi-)automatische Unterstützung bei der digitalen Erschließung von Sammlungsbeständen

**Erstellung eines Korpus mit Trainingsbilddaten für die automatische Genreklassifikation**

Die digitale Erschließung von Sammlungsbeständen spielt eine zentrale Rolle in der modernen Forschungs- und Sammlungsarbeit. Insbesondere bei umfangreichen und heterogenen Datenbeständen, wie sie etwa in der Digitalisierung von Liebesbriefen, bis Computerspielen vorkommen, stellen (semi-)automatische Lösungen eine Unterstützung dar. Ziel ist es, die manuelle Klassifikationsarbeit zu optimieren, indem automatische Vorschläge zur Genreklassifikation erstellt und bestehende Zuordnungen überprüft werden.

Nicht nur im Kontext von Computerspielen ist die Genreklassifikation eine komplexe Aufgabe. Viele Objekte lassen sich nicht eindeutig einer Kategorie zuordnen, und die Vielzahl an Genres sowie deren Überschneidungen erfordern Fachkenntnis und gut kuratierte Daten. Ein entscheidender Schritt in diesem Prozess ist die Erstellung eines geeigneten Korpus mit Trainingsbilddaten, das die Grundlage für die Entwicklung und Optimierung eines Klassifikationsmodells bildet.

Diese Einheit vermittelt die grundlegenden Schritte und Methoden zur Erstellung eines Korpus zur Entwicklung eines Ausgangsdatenformats für Klassifikationsarbeiten. Dabei spielen technische als auch kuratorische Aspekte, von der Auswahl und Aufbereitung relevanter Bilddaten über die Annotation mit Metadaten bis hin zur Sicherstellung der Datenqualität aber auch der Berücksichtigung ethischer und rechtlicher Rahmenbedingungen eine Rolle. 

Das Ziel dieser Einheit 1 von 5 ist es, ein standardisiertes und belastbares Ausgangsdatenformat zu entwickeln, das die automatische Genreklassifikation am Beispiel von Computerspielen und Liebesbriefen ermöglicht.

Die Einheit ist Teil der Reihe „(Semi-)automatische Unterstützung bei der digitalen Erschließung von Sammlungsbeständen“ und adressiert damit zentrale Herausforderungen in der Archiv- und Sammlungsarbeit. Durch die Anwendung der hier vermittelten Inhalte können Teilnehmende einen wesentlichen Beitrag zum effizienteren und nachhaltigeren Aufbau und der Nachnutzung von digitalen Beständen leisten.

**Übergeordnetes Lernziel** dieser Einheit ist es, einen Korpus für die Genreklassifikation vorzubereiten um eine automatische klassifikation durchzuführen. (siehe LZ-ID_0587)

## Zielgruppe

Diese Lerneinheit richtet sich an Forschende mit universitären wissenschaftlichen Sammlungen, die Interesse haben das Arbeiten mit Jupyter Notebooks kennenzulernen, zu erproben und zu vertiefen.

**Vorausetzung**

Lernende können 
...
- eigenständig Datenbankabfragen durchführen (anwenden) (LZ-ID_402)
- Methoden zum Datenexport anwenden (LZ-ID_0412)
- Datenexport erzeugen (anwenden) (LZ-ID_417)


## Lernziele

**FDM-Grundlagen** 

- klares Forschungsziel mit einer Forschungsfrage für eine Datenerhebung entwickeln (LZ-ID_0543)
- die Qualität einer Forschungsfrage analysieren (LZ-ID_0544)
- die Qualität udn Eignung von Daten für eine spezifische Forschungsfrage bewerten (LZ-ID_0885)

- den Begriff Klassifikation erläutern (LZ-ID_720)
- Beispiele von Klassifikationen benennen und erläutern (LZ-ID_731, 732)
- Klassifikationen zur Beschreibung von Resourcen benennen bis entwickeln (LZ-ID_0736-0741)


**OER-spezifische Data-Science-Aspekte**

- Klassen für Klassifikationsaufgabe benennen (neu)
- Multi-Labels benennen (neu)
- Labelspace entwickeln (neu)
- eigene Daten analysieren, bewerten und entwickeln (neu) 
- benötigtes Ausgangsformat entwickeln (neu)

**Weiterführende Einheiten**

- Methoden zur Datenbereinigung in realen Szenarien anwenden (LZ-ID_0468)
- Software zur Datananalyse anwenden (LZ-ID_0578)


## Didaktisches Konzept

**Inhalte**

Diese OER ermöglicht den Teilnehmenden, aktiv und praxisnah einen Trainingskorpus für die automatische Genreklassifikation zu erstellen. Gleichzeitig entwickeln sie ein kritisches Verständnis für Datenqualität, Datei- und Ordnerstrukturen und erhalten Verweise auf weiterführende vertiefende Inhalte zu ethischen Fragen und Herausforderungen in der digitalen Erschließung.

**Lernform**

Das didaktische Konzept im Sinne des forschenden Lernens für diese OER basiert auf fünf Phasen (in Anlehnung an Sonntag, M., Rueß, J., Ebert, C., Friederici, K., Schilow, L. und Deicke, W. (2018)
Forschendes Lernen im Seminar - Ein Leitfaden für Lehrende. 2. überarbeitete Auflage. Berlin : Humboldt-Universität zu Berlin. 112 S. mit Abb. verfügbar unter https://www.researchgate.net/publication/323030033): 

(1) Problemfindung

Der Einstieg in das Thema findet mit einer realen Problemstellung statt. Die Herausforderungen der Genreklassifikation in Computerspiel-Sammlungen werden erörtert und bestehende Ansätze verglichen. 

Forschungsleitfragen werden formuliert, wie z.B.

- Welche Merkmale von Bildern sind für die automatische Genreklassifikation relevant?
- Welche Datenquellen sind geeignet, um ein repräsentatives Trainingskorpus zu erstellen?

(2) Exploration

Eine bestehende Datenquelle wird erkundet und hinsichtlich des Erschließungsumfangs und der Datenqualität kritisch bewertet.


(3) Methodenanwendung

Eine Auswahl relevanter Bilddaten wird aufbereitet, mit Genre-Labels annotiert und ein standardisiertes Ausgangsformat für das maschinelle Lernen generiert. 


(4) Reflexion

Das Korpus wird hinsichtlich der Repräsentativität, Herausvorderungen, Grenzen und Optimierungsmöglichkeiten erörtert.

(5) Präsentation & Transfer

Der Prozess der Korpuserstellung wird in einem kleinen Bericht/ kleine Abschlußpräsentation zusammengefasst.

**Lernmethoden und -formate**

In dem synchronen Lernsetting dieser Lerneinheit erfolgt die Taktung der Lernbausteine innerhalb der Einheit nach den Lernzielen und folgt dem Lernmodell nach Klaus Döring (Döring, Klaus W. Handbuch Lehren und Trainieren in der Weiterbildung. Weinheim: Beltz, 2008. S. 57–58).

Jeder Lernbaustein beginnt mit einem kurzen Wissensimpuls in Form eines Vortrags, bei dem das Interesse der Lernenden geweckt und das individuelle Vorwissen aktiviert wird. Dadurch können Lernende das vermittelte Wissen aufnehmen und reflektieren. In einer begleiteten Praxisübung wenden die Lernenden das neue Wissen an und festigen es im Austausch mit anderen Teilnehmenden. Durch den Diskurs in der Gruppe wird das Gelernte vertieft. In der anschließenden Vertiefungsphase werden weitere Anwendungsbeispiele vorgestellt und besprochen, so dass Lernende das individulle Wissen Praxisbezogen erweitern können. In der abschließenden Phase erfolgt ein selbstständiger Wissenstransfer, bei dem die Lernenden das Gelernte weiterentwickeln oder anpassen. Dadurch wird ein iterativer Wissensaufbau sichergestellt.

**Materialien**

Benötigt wird ein eigenes Laptop.

**Feedback**

Der Lernerfolg wird über die Lernziele sicher gestellt und über die Abschlußpräsentation überprüfbar.

Zur Verbesserung der Lerneinheit wird von den Teilnehmenden ein anonymes Feedback eingeholt.

 
To see this document as an interactive LiaScript rendered version, click on the
ollowing link/badge:

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/chastik/Spielplatz/main/Liascript_test.md)

![CC-BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)
This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).



