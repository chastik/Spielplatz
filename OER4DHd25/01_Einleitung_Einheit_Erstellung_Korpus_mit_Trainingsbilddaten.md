<!--

author: Mathias Zinnen und Canan Hastik  
email:    
version:  v1
language: DE

icon:     https://raw.githubusercontent.com/chastik/Beratung_Dateityp_Bild/refs/heads/main/SODa-Logo_full.svg
link:     https://raw.githubusercontent.com/chastik/Beratung/refs/heads/main/soda.css

comment:  WissKi SODA OERs

-->

# Willkommen zu SODa OERs 

**Modul: (Semi-)automatische Unterstützung bei der digitalen Erschließung von Sammlungsbeständen**

*Motivational Design und Nutzen*

Die Reihe „(Semi-)automatische Unterstützung bei der digitalen Erschließung von Sammlungsbeständen“ hilft Ihnen, zentrale Herausforderungen in der Archiv- und Sammlungsarbeit effizient zu meistern. In fünf praxisnahen Einheiten lernen Sie, wie Sie digitale Bestände gezielt aufbauen und nachhaltig für die Nachnutzung optimieren können.

In Einheit 1 entwickeln Sie ein strukturiertes und belastbares Ausgangsdatenformat für einen Beispielbestand. Dabei legen Sie die Grundlage für eine automatische Genreklassifikation von Bilddatenbeständen – von Computerspielen bis hin zu Liebesbriefen. Mit diesem Wissen können Sie nicht nur die Qualität Ihrer digitalen Erschließung verbessern, sondern auch innovative Analyse- und Anwendungsmöglichkeiten erschließen.


## Kurzbeschreibung der Lerneinheit

**Lerneinheit: Erstellung eines Korpus mit Trainingsbilddaten für die automatische Genreklassifikation**

Die digitale Erschließung von Sammlungsbeständen spielt eine zentrale Rolle in der modernen Forschungs- und Sammlungsarbeit. Insbesondere bei umfangreichen und heterogenen Datenbeständen, wie sie etwa in der Digitalisierung von Liebesbriefen, bis Computerspielen vorkommen, stellen (semi-)automatische Lösungen eine Unterstützung dar. Ziel ist es, die manuelle Klassifikationsarbeit zu optimieren, indem automatische Vorschläge zur Genreklassifikation erstellt und bestehende Zuordnungen überprüft werden.

Nicht nur im Kontext von Computerspielen ist die Genreklassifikation eine komplexe Aufgabe. Viele Objekte lassen sich nicht eindeutig einer Kategorie zuordnen, und die Vielzahl an Genres sowie deren Überschneidungen erfordern Fachkenntnis und gut kuratierte Daten. Ein entscheidender Schritt in diesem Prozess ist die Erstellung eines geeigneten Korpus mit Trainingsbilddaten, das die Grundlage für die Entwicklung und Optimierung eines Klassifikationsmodells bildet.

Diese Einheit vermittelt die grundlegenden Schritte und Methoden zur Erstellung eines Korpus zur Entwicklung eines Ausgangsdatenformats für Klassifikationsarbeiten. Dabei spielen technische als auch kuratorische Aspekte, von der Auswahl und Aufbereitung relevanter Bilddaten über die Annotation mit Metadaten bis hin zur Sicherstellung der Datenqualität aber auch der Berücksichtigung ethischer und rechtlicher Rahmenbedingungen eine Rolle. 

### Zielgruppe

*Neugier wecken*

Diese Lerneinheit richtet sich an Forschende mit universitären wissenschaftlichen Sammlungen, die Interesse haben das Arbeiten mit Jupyter Notebooks kennenzulernen, zu erproben und zu vertiefen.

Wie lassen sich wissenschaftliche Sammlungen effizienter digital erschließen? Wie können Jupyter Notebooks dabei helfen, Daten zu analysieren und zu strukturieren?

Diese Lerneinheit richtet sich an Forschende mit universitären wissenschaftlichen Sammlungen, die neue digitale Methoden entdecken und gezielt für ihre Arbeit nutzen möchten. Sie erhalten die Möglichkeit, Jupyter Notebooks praxisnah kennenzulernen, auszuprobieren und gezielt einzusetzen – sei es für automatisierte Datenverarbeitung, Visualisierung oder die Strukturierung großer Sammlungsbestände.

Ob Sie erste Erfahrungen mit Jupyter sammeln oder Ihr Wissen vertiefen möchten – diese Einheit bietet Ihnen konkrete Lösungen ist skalierbar für typische Herausforderungen in der digitalen Sammlungsarbeit.

### Übergeordnetes Lernziel und Voraussetzungen

*Storytelling:Gaming,GLAM,LOD,SemanticWeb*

In dieser Einheit wird ein Korpus für die Genreklassifikation vorbereitet um eine automatische Klassifikation durchzuführen. (siehe LZ-ID_0587)

Während das Forschungsdatenmanagement (FDM) die Grundlage für nachhaltige und transparente Wissenschaft bildet, lassen sich durch die Integration von Data Science-Methoden diese Kompetenzen gezielt erweitern und an aktuelle Anforderungen anpassen.

Lernende können bereits...

- eigenständig Datenbankabfragen durchführen (anwenden) (LZ-ID_402)
- Methoden zum Datenexport anwenden (LZ-ID_0412)
- Datenexport erzeugen (anwenden) (LZ-ID_417)


# Didaktisches Konzept

Diese Einheit ermöglicht den Teilnehmenden, aktiv und praxisnah einen Trainingskorpus für die automatische Genreklassifikation zu erstellen. Gleichzeitig entwickeln sie ein kritisches Verständnis für Datenqualität, Datei- und Ordnerstrukturen und erhalten Verweise auf weiterführende vertiefende Inhalte zu ethischen Fragen und Herausforderungen in der digitalen Erschließung.

## Lernziele

Durch die Verbindung von Forschungsdatenmanagement und Data Science entstehen Synergien, die den wissenschaftlichen Erkenntnisgewinn beschleunigen, die Datenqualität verbessern und die nachhaltige Nutzung von Forschungsdaten fördern. Themen umfassen: Datenerheben, Datentypen, Datenqualität, Taxonomie, Klassifikationsverfahren, Mustererkennung, ...

### FDM-Grundlagen

- klares Forschungsziel mit einer Forschungsfrage für eine Datenerhebung entwickeln (LZ-ID_0543)
- die Qualität einer Forschungsfrage analysieren (LZ-ID_0544)
- die Qualität und Eignung von Daten für eine spezifische Forschungsfrage bewerten (LZ-ID_0885)

### Grundlagen der Datenaufbereitung

- den Begriff Klassifikation erläutern (LZ-ID_720)
- Beispiele von Klassifikationen benennen und erläutern (LZ-ID_731, 732)
- Klassifikationen zur Beschreibung von Resourcen benennen bis entwickeln (LZ-ID_0736-0741)
- eigene Datentypen oder Datenqualität analysieren (.... was genau?) 

### Einführung in die Bildklassifikation

- Klassen für Klassifikationsaufgabe benennen (neu)
- Multi-Labels benennen (neu)
- Labelspace entwickeln (neu)
- benötigtes Ausgangsformat entwickeln (neu)

### Ausblick: Weiterführende vertiefende Einheiten

- eigenständig Maßnahmen zur Implementierung der FAIR-Prinzipien anwenden (LZ-ID-0125)
- Methoden zur Datenbereinigung in realen Szenarien anwenden (LZ-ID_0468)
- Software zur Datananalyse anwenden (LZ-ID_0578)
- Klassifikationsverfahren für die Mustererkennung (...?)


## Lernform

Das didaktische Konzept im Sinne des forschenden Lernens für diese OER basiert auf fünf Phasen (in Anlehnung an Sonntag, M., Rueß, J., Ebert, C., Friederici, K., Schilow, L. und Deicke, W. (2018)
Forschendes Lernen im Seminar - Ein Leitfaden für Lehrende. 2. überarbeitete Auflage. Berlin : Humboldt-Universität zu Berlin. 112 S. mit Abb. verfügbar unter https://www.researchgate.net/publication/323030033): 

**Problemfindung**

Der Einstieg in das Thema findet mit einer realen Problemstellung statt. Die Herausforderungen der Genreklassifikation in Computerspiel-Sammlungen werden erörtert und bestehende Ansätze verglichen. 

Forschungsleitfragen werden formuliert, wie z.B.

- Welche Merkmale von Bildern sind für die automatische Genreklassifikation relevant?
- Welche Datenquellen sind geeignet, um ein repräsentatives Trainingskorpus zu erstellen?

**Exploration**

Eine bestehende Datenquelle wird erkundet und hinsichtlich des Erschließungsumfangs und der Datenqualität kritisch bewertet.


**Methodenanwendung**

Eine Auswahl relevanter Bilddaten wird aufbereitet, mit Genre-Labels annotiert und ein standardisiertes Ausgangsformat für das maschinelle Lernen generiert. 


**Reflexion**

Das Korpus wird hinsichtlich der Repräsentativität, Herausvorderungen, Grenzen und Optimierungsmöglichkeiten erörtert.


**Präsentation & Transfer**

Der Prozess der Korpuserstellung wird in einem kleinen Bericht/ kleine Abschlußpräsentation zusammengefasst.


## Lernmethoden und -formate

In dem synchronen Lernsetting dieser Lerneinheit erfolgt die Taktung der Lernbausteine innerhalb der Einheit nach den Lernzielen und folgt dem Lernmodell nach Klaus Döring (Döring, Klaus W. Handbuch Lehren und Trainieren in der Weiterbildung. Weinheim: Beltz, 2008. S. 57–58).

Jeder Lernbaustein beginnt mit einem kurzen Wissensimpuls in Form eines Vortrags, bei dem das Interesse der Lernenden geweckt und das individuelle Vorwissen aktiviert wird. Dadurch können Lernende das vermittelte Wissen aufnehmen und reflektieren. In einer begleiteten Praxisübung wenden die Lernenden das neue Wissen an und festigen es im Austausch mit anderen Teilnehmenden. Durch den Diskurs in der Gruppe wird das Gelernte vertieft. In der anschließenden Vertiefungsphase werden weitere Anwendungsbeispiele vorgestellt und besprochen, so dass Lernende das individulle Wissen Praxisbezogen erweitern können. In der abschließenden Phase erfolgt ein selbstständiger Wissenstransfer, bei dem die Lernenden das Gelernte weiterentwickeln oder anpassen. Dadurch wird ein iterativer Wissensaufbau sichergestellt.

## Konzeption der Inhalte

01_Einheit_FDM_Grundlagen
02_Einheit_Grundlagen_Datenaufbereitung
03_Einheit_Einführung_Bildklassifikation


# Methodisches Konzept: Modulare Struktur mit Drehbuch

01_Einheit_FDM_Grundlagen
02_Einheit_Grundlagen_Datenaufbereitung
03_Einheit_Einführung_Bildklassifikation


# Technisches Konzept


**Materialien**



**Feedback**

Der Lernerfolg wird über die Lernziele sicher gestellt und über die Abschlußpräsentation überprüfbar.

Zur Verbesserung der Lerneinheit wird von den Teilnehmenden ein anonymes direktes Feedback eingeholt. (ToDO)

Ferner können Metriken und Daten von GitHub genutzt werden, um die Aktivitäten und Beteiligungen in einem Repo oder einer Organisation, dem Traffic, den Commits, den Status von Pull Requests und Issues sowie das Community-Engagement nachzuvollziehen. Mit der von GitHub zur Verfügung gestellten API können Repository-Metriken abgerunfen, Beitragsanalysen ermittelt und Entwicklungstrends erkannt werden.


# Bibliographie

Döring, Klaus W. Handbuch Lehren und Trainieren in der Weiterbildung. Weinheim: Beltz, 2008. S. 57–58
LZM
E-Learning Grundlagen, FHWien der WKW, Christopher Könitz & Anastasia Baillie-Spegalskaya
Sonntag, M., Rueß, J., Ebert, C., Friederici, K., Schilow, L. und Deicke, W. (2018)
Forschendes Lernen im Seminar - Ein Leitfaden für Lehrende. 2. überarbeitete Auflage. Berlin : Humboldt-Universität zu Berlin. 112 S. mit Abb. verfügbar unter https://www.researchgate.net/publication/323030033)


To see this document as an interactive LiaScript rendered version, click on the
ollowing link/badge:

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/chastik/Spielplatz/main/Liascript_test.md)

![CC-BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)
This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
