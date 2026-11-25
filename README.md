# VokabelFoto

Vokabelliste aus deinem Buch (z. B. Green Line) fotografieren, Seiten zuordnen und gezielt lernen:
Karteikarten, Multiple Choice, Tippen und Zuordnen. Falsche Wörter kommen öfter dran (5 Fächer wie bei der Lernkartei).

## Auf GitHub veröffentlichen

1. Neues Repository auf github.com anlegen, mit dem Namen `DEIN-NAME.github.io`.
2. `index.html` und diese `README.md` hochladen (Add file → Upload files).
3. Settings → Pages → Branch `main`, Ordner `/ (root)` → Save.
4. Nach ca. einer Minute läuft die App unter `https://DEIN-NAME.github.io/`.

Auf dem Handy: Link öffnen und im Browser-Menü „Zum Startbildschirm hinzufügen“ wählen.

## Hinweise

- Die Texterkennung nutzt [Tesseract.js](https://github.com/naptha/tesseract.js) und braucht beim Scannen Internet. Gelernt werden kann danach auch offline, solange die Seite geladen ist.
- Deine Wörter liegen nur lokal im Browser. Unter „Wörter“ kannst du sie als JSON sichern und wieder laden.
- Am besten erkannt werden Listen mit einem Paar pro Zeile, getrennt durch `-`, `:`, `=` oder einen größeren Abstand.
