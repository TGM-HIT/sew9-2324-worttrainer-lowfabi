# 9a.1: Worttrainer Reloaded
## Inhalt
- [Aufgabenstellung](#task)

  - [Funktionen](#funktionen)

- [Ausarbeitung](#ausarbeitung)

  - [GUI](#gui)
  - [Persistenz](#persistenz)

- [Installation](#installation)

## Task
Für einen Rechtschreibtrainer für Wörter (Zielgruppe Volksschulkinder)  soll ein erster Entwurf der Funktionalität erstellt werden. Die Kinder  sollen dabei zu einem Bild (z.B. einem Hund) das entsprechende Wort  eintippen. Dieses Wort wird dann mit der richtigen Schreibweise  verglichen und eine entsprechende Meldung wird angezeigt.

### Funktionen

- Benutzeranmeldung und Registrierung
- Anzeige von Wörtern und Bildern
- Wort und das zugehörige Bild für alle Benutzer hinzufügen
- Statistiken anschauen
- Das Spiel neu starten

## Ausarbeitung 

Grundsätzlich wurde die Aufgabe nach der [Angabe von der S09-GK9a1](https://elearning.tgm.ac.at/mod/assign/view.php?id=77461) Aufgabe gestaltet. In diesem README beschreibe ich nur die die Dinge, welche ich anders gestalte zur aufklärung.

### GUI

Die GUI wurde anders als in der [Angabe von der S09-GK9a1](https://elearning.tgm.ac.at/mod/assign/view.php?id=77461) mittels JavaFX gemacht und nicht nur mittels JOptionPane. Dies ist einfacher, übersichtlicher und grunsätzlich praktischer.

### Persistenz 

Eine Worttrainer-Session (bestehend aus den zur Verfügung stehenden  Wort-Bild-Paaren, dem aktuell ausgewählten Paar (falls vorhanden) sowie  der aktuellen Statistik) soll auch gespeichert werden können. Dies habe ich gemacht in dem ich [TODO].

## Installation

1. Laden Sie das Projekt von GitHub herunter oder klonen Sie es auf Ihren lokalen Computer.
2. Stellen Sie sicher, dass Sie JDK 11 oder höher installiert haben.
3. Stellen Sie sicher, dass Sie Gradle 6.8.3 oder höher installiert haben.
4. Stellen Sie sicher, dass Sie eine SQL-Datenbank installiert haben und konfigurieren Sie die Verbindung in `DatabaseHandler`.
5. Führen Sie `gradle run` aus, um die Anwendung auszuführen.
