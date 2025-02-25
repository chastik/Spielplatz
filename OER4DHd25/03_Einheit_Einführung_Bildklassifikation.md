<!--

author: Mathias Zinnen und Canan Hastik  
email:    
version:  v1
language: DE

icon:     https://raw.githubusercontent.com/chastik/Beratung_Dateityp_Bild/refs/heads/main/SODa-Logo_full.svg
link:     https://raw.githubusercontent.com/chastik/Beratung/refs/heads/main/soda.css

comment:  WissKi SODA OERs

-->


# Einheit 03: Vorbereitung der Bildklassifikation
In dieser Einheit wenden die Lernenden die in Einheit 01 präzisierte Fragestellung mit Hilfe der in Einheit 02 erlernten theoretischen Grundlagen auf die eigenen Daten an um das Training eines Klassifikationsalgorithmus vorzubereiten.

# Ziel: Die Lernenden vertiefen das zuvor vermittelte Wissen in der Anwendung auf ein konkretes Beispiel

## Themen und Methoden:
- Klassen für Klassifikationsaufgabe herausarbeiten (neu)
    - Ziel: Die Lernenden entwickeln ein konkretes Klassenschema aus ihren Daten und ihrer Fragestellung
    - Praxisübung: Die Lernenden arbeiten mögliche Kategorien zur Klassifikation heraus. 
    - Diskussion: Sind auch andere Klassen denkbar? Können mehrere Klassen vereinheitlicht werden? Wenn ja, wie?

- Art der Klassifikation benennen (neu)
    - Ziel: Die Lernenden können zwischen Multi-Label und Single-Label Klassfikation unterscheiden
    - Impuls: Kurze Wiederholung der in Einheit 2 vermittelten Konzepte
    - Praxisübung: Die Lernenden entscheiden, ob die vorher formulierte Fragestellung und die Datenbasis sich als Multi-Label oder Single-Label Klassifikation formulieren lässt.
    - Diskussion: Gibt es Probleme die sich als beides modellieren lassen? Inwieweit ist die Modellierung einer Forschungsfrage als Klassifikationsproblem eine subjektive Entscheidung?

- Benötigtes Ausgangsformat entwickeln (neu)
    - Ziel: Die Lernenden können ihre eigenen Daten in ein vom Klassifikationsalgorithmus benötigtes Format bringen. Das beinhaltet Dateistruktur und Datenrepräsentation der Labels
    - Impuls: Exemplarisch wird ein Datenformat vorgestellt. Ein Skript zur Überführung des bestehenden in das benötigte Datenformat wird zur Verfügung gestellt und erklärt.
    - Praxisübung: Die Teilnehmenden passen das Skript an (z.B. durch Setzen von Pfaden in das Dateisystem.) und beobachten die Auswirkungen.
    - Diskussion: Welche weiteren Datenformate (Dateistruktur, Labeldarstellung) sind denkbar. Haben multilabel Probleme andere Anforderungen als single-label?