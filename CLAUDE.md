# Blastopia: Hinweise für Claude

Handy-Spiel (Querformat), Solo-Projekt. Sprache mit dem Entwickler: Deutsch.

## Grafiken und Bilder

Wenn für etwas Grafiken oder Bilder gebraucht werden (Figuren, Icons, Hintergründe, Store-Bilder, Logos usw.), **nicht selbst zeichnen oder Platzhalter erfinden**, sondern:

1. Einen fertigen Prompt schreiben, den der Entwickler kopieren kann (auf Englisch, mit Format, Stil, Inhalt und was ausgeschlossen werden soll).
2. Dazu sagen, mit welcher Bild-KI sich das am besten umsetzen lässt, und warum.
3. Der Entwickler lädt das Ergebnis im Chat hoch, dann wird es eingebaut.

Stilvorgaben aus dem Titelbild (`title.jpg`): kräftige 2D-Cartoon-Optik, dicke dunkle Konturen, flache Farben mit weicher Schattierung, Palette Orange, Sandbeige, Schieferblau, Lila. Kein Text im Bild, eigene Figuren, keine Ähnlichkeit zu Bomberman oder Brawl Stars.

## Helden (Aussehen laut Titelbild)

- **Rex:** orange, stachelige orange Haare, wirft Bomben
- **Lumi:** hellgelb, Antenne mit leuchtender Glühbirne
- **Mimik:** braun, trägt eine Holzkiste als Hut
- **Schatten:** dunkellila, schwarze Augenmaske, stachelige Haare

## Dateien

- `index.html`: kompletter Browser-Prototyp, läuft über GitHub Pages
- `title.jpg`: Titelbild (Startbildschirm und Menü-Hintergrund)
- `icons/`: Power-up- und Stern-Icons (192 px PNG, mit ChatGPT erstellt, Hintergrund entfernt)
- `heroes/`: Spielfiguren Rex, Lumi, Mimik, Schatten (192 px PNG, mit ChatGPT nach Vorlage des Titelbilds erstellt). Endgegner nutzen dieselben Bilder mit Farbfilter.
- `TESTEN.md`: Testanleitung für Tester
