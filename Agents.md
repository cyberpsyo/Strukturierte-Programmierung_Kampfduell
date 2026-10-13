# Anweisungen für Agenten

Grundlegende Anweisungen für KI-Assistenten, die an diesem Repository arbeiten.

## Projektkontext

- Duel Fighter ist ein rundenbasiertes Kampfspiel für die Konsole, programmiert in Java.
- Es ist ein Uni-Projekt für die Lehrveranstaltung Strukturierte Programmierung (1. Semester).
- Die Beschreibung steht in `readme.md`, die nummerierte Liste der Features in `features.md`.

## Technische Regeln

- Sprache: Java (JDK 17 oder neuer), nur Konsolenanwendung.
- Der gesamte Code steht in einer Datei: `DuelFighter.java`.
- Das ganze Programm wird in der `main`-Methode geschrieben.
- Nur die Themen der Lehrveranstaltung verwenden: Input, Berechnungen, Output, Selections (`if/else`, `switch`) und Loops (`while`, `do-while`, `for`).
- Keine eigenen Klassen (außer der Hauptklasse), keine Arrays, keine Collections, keine Dateien, keine externen Bibliotheken und keine grafische Oberfläche.
- `Scanner` für Eingaben und `Math.random()` für Zufallszahlen verwenden.

## Code-Stil

- Klare, aussagekräftige Variablennamen verwenden (z. B. `spielerLp`, `computerAktion`).
- Kurze Kommentare schreiben, die jeden Teil des Programms erklären (Eingabe, Berechnung, Ausgabe).
- Den Code einfach und gut lesbar für Studierende im ersten Semester halten.
- Alle Texte in der Konsole sind auf Deutsch.

## Arbeitsweise

- Der Autor lernt gerade programmieren. Änderungen in einfachen Worten erklären.
- Lieber erklären und Hinweise geben, statt die komplette Lösung zu schreiben.
- Nur Features umsetzen, die in `features.md` aufgelistet sind.
- In kleinen Schritten arbeiten und nach jedem Schritt testen.

## Ausführen

```bash
javac DuelFighter.java
java DuelFighter
```
