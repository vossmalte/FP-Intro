# Begrüßung

## Willkommen

... über mich

- studiere Mathematik und Informatik auf Lehramt
- bin seit 2015 am KIT
- spiele in meiner Freizeit Frisbee
- habe in meiner Bachelorarbeit neuronale Netze für Bewegungserkennung in der Robotik eingesetzt
- wohne in der Karlsruher Oststadt

## Über euch

Stellt euch bitte kurz vor:

- Wie heißt du?
- Wo wohnst du?
- Hast du schon mal programmiert? Wenn ja, was?
- Hattest du Informatik in der Schule?
- Wo stehst du gerade im Studium? Schon in Karlsruhe angekommen?

# Programmieren

## Organisatorisches

- Folien lade ich im ILIAS hoch
- Tutoren sind die ersten Ansprechpartner für die Vorlesung
- Wie und wo stellt man Fragen?
    - FAQ auf der Homepage
    - Wiki im ILIAS
    - Im Forum gibt es die Frage
    - Im Forum die Frage stellen
    - Tutor fragen
    - Übungsleitung fragen

## Struktur des Moduls

- Der Übungsschein ist Voraussetzung für die Teilnahme an den Abschlussaufgaben
- Die Abschlussaufgaben sind benotet
- Voraussetzungen für den Übungsschein:
    - mehr als 50% auf den Übungsblättern
    - Präsenzübung
- euer Tutor korrigiert eure Übungsblätter

## Präsenzübung

- Präsenzübung ist eine schriftliche Prüfung
- Dieses Semester: Vorrechnen im Tutorium als Alternative zur Präsenzübung

## Gruppenarbeit

- manche Aufgaben werden im Team abgegeben
- ein Team besteht aus 3 Personen
- alle Personen müssen im gleichen Tutorium sein
- alle Personen geben das gleiche ab

\pause

- bildet bitte jetzt Teams
- Teams werden notiert

## Inhalte des Tutoriums

- Themen aus der Vorlesung wiederholen
- Übungsblätter besprechen
- kleine Programmieraufgaben
- Fragen beantworten
\pause
- __Ihr entscheidet, was wir im Tutorium machen__

## Wichtig

- Einverständniserklärung / Disclaimer abgeben
- im Praktomaten anmelden
    - VPN installieren
- im ILIAS anmelden

# Java - Start

## Java: Installation

- OpenJDK eignet sich als Entwicklungsumgebung
    - `sudo apt-get install openjdk-11-jdk` oder adoptopenjdk.net
- Windows: Umgebungsvariablen setzen!
- in der CMD oder im Terminal testen:
    - `java --version` und `javac --version`

## Java: Mein erstes Programm

~~~{.java}
class Programm {
    public static void main(String[] args) {
        System.out.println("Hallo :-)");
    }
}
~~~

\pause

- Kompilieren: `javac Programm.java`
- Ausführen: `java Programm`

## Eine kleine Einführng in CMD / bash

- `dir` / `ls` zeigt die Inhalte des aktuellen Ordners an
- mit `cd` kann man das Verzeichnis wechseln (`..` ist "zurück")

\pause

- Windows unterstützt das Windows Subsystem für Linux
- Auf Windows gibt es PowerShell, das funktioniert wie bash

# Objekte und Klassen

## Objektorientierung

- Objekt-orientierte Programmierung ist das Mantra dieser Vorlesung

- Begriffe: Objekt, Klasse

\pause

- Objekte sind Abstrahierungen der realen Welt
- Klassen sind Baupläne der Objekte
- Die Eigenschaften von Objekten werden _Attribute_ genannt

\pause

- `Car meinAuto = new Car();` erzeugt ein neues Objekt der Klasse Car

## Aufgabe

- modelliert ein Auto
- mögliche Aspekte auf Papier festhalten oder direkt in Java implementieren

# Datentypen

## Datentypen - Übersicht

- ganze Zahlen `int, byte, short, long`
- Text: `String`
- Kommazahlen: `double, float`
- Wahrheitswerte: `boolean`

## Datentypen - Operatoren

- `+,-,*,/`
- Mit Operatoren kann man Daten verknüpfen: `1+2`
\pause
- teste, welche Ergebnisse jeweils herauskommen:
    - `9/2`
    - `1 + 1/2`
    - `5 * 0.5`
    - `7 + "Hallo"`
- testen, z.B. mit `System.out.println(1+2)`

##

\centering

~~~{=latex}
\includegraphics[keepaspectratio,height=0.8\textheight]{01/abstraction.png}
~~~

<!---![xkcd: Abstraction](01/abstraction.png){height=80%,keepaspectratio}-->
