SPANISHGYMCLASS – FLACHES GITHUB-PAKET
=====================================

Alle Dateien in diesem Ordner gehören direkt in das Hauptverzeichnis des neuen GitHub-Repositories "SpanishGymClass".
Es gibt absichtlich KEINE Unterordner.

UPLOAD AUF GITHUB
1. Neues öffentliches Repository "SpanishGymClass" erstellen.
2. Im leeren Repository: "Add file" -> "Upload files".
3. Diesen ZIP-Ordner lokal ENTPACKEN.
4. Im entpackten Ordner ALLE Dateien markieren (nicht den Ordner selbst / nicht die ZIP-Datei).
5. Die markierten Dateien gemeinsam in die GitHub-Uploadfläche ziehen.
6. Commit changes.
7. Settings -> Pages -> Deploy from a branch -> main / (root) -> Save.

WICHTIG
- index.html, content.js und alle .webp-Dateien müssen auf derselben Ebene liegen.
- Die App speichert Lernfortschritt ausschließlich lokal im Browser (localStorage).
- Es gibt bewusst keinen Service Worker in dieser ersten Unterrichtsversion. Dadurch kann keine alte Cache-Version mit der neuen App interferieren.
- Die App benötigt für den ersten Aufruf Internetzugang zu GitHub Pages; danach kann der Browser einzelne Ressourcen normal zwischenspeichern, aber Offline-Betrieb ist nicht garantiert.

ENTHALTEN
- 24 konsistente Avatare (neutral + Jubelzustand)
- Übungsmodus und Challenge Builder für Unidad 1 und 2
- Fitness Clash mit Gewinner-Avatar und Konfetti
- Final Bosse mit Timer, 80%-Siegschwelle und Gold/Silber/Bronze-Platzierung
- Boss-Sprüche nach Sieg/Niederlage
- Hall of Fame mit 24 Auszeichnungen
- 8 Sportwelten / Hintergründe
- Smartphone-optimierte Sonderzeichenzeile oberhalb des Eingabefelds
