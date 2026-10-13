# Strukturierte-Programmierung_Kampfduell

**Autor:** Musa Bisaev
**Lehrveranstaltung:** Strukturierte Programmierung, 1. Semester

## Beschreibung

Duel Fighter ist ein rundenbasiertes Kampfspiel für die Konsole, programmiert in Java.
Der Spieler kämpft gegen einen Computergegner. Beide Kämpfer starten mit 100 Lebenspunkten (LP).

In jeder Runde wählt der Spieler eine Aktion (Schlag, Tritt oder Block). Der Computer wählt seine Aktion gleichzeitig per Zufall, sodass keine Seite die Wahl der anderen im Voraus kennt. Nachdem beide Aktionen aufgedeckt sind, wird der Schaden berechnet und von den Lebenspunkten abgezogen. Der Kampf geht weiter, bis ein Kämpfer 0 LP oder weniger hat. Am Ende wird der Sieger angezeigt und der Spieler kann eine neue Runde starten.

## Regeln

| Aktion | Wirkung |
|---|---|
| Schlag | Verursacht 8 bis 12 Schaden, trifft immer |
| Tritt | Verursacht 12 bis 20 Schaden, trifft aber nur mit 60 % Wahrscheinlichkeit |
| Block | Halbiert den Schaden des Gegners in dieser Runde |

## Behandelte Themen

- **Input:** Spielername, Aktion pro Runde, Frage „Nochmal spielen?“ (mit `Scanner`)
- **Calculate:** Zufallsschaden, Trefferchance, Schadensreduktion durch Block, Abzug der Lebenspunkte, Rundenzähler
- **Output:** Lebenspunkte beider Kämpfer, gewählte Aktionen, Schaden pro Runde, Sieger und Anzahl der Runden
- **Selections:** `switch` für die gewählte Aktion, `if/else` für Treffer, Block und Siegerermittlung
- **Loops:** `while`-Schleife für die Kampfrunden, `do-while`-Schleifen für die Eingabeprüfung und das erneute Spielen
