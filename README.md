# Grevo

Erfolge, Ziele und Kudos festhalten, damit am Jahresende nichts fehlt. Im Design der Familienkasse.

- **Übersicht:** dein Jahr auf einen Blick, Ziel-Fortschritt, letzte Kudos, Erinnerung nach 14 Tagen ohne Eintrag
- **Erfolge:** suchen, filtern (Jahr, Bereich, Wirkung, Highlights), bearbeiten, Anhänge, mit Zielen verknüpfen
- **Ziele:** Fortschritt über die Zahl verknüpfter Erfolge
- **Kudos:** Lob sammeln
- **Rückblick:** Jahr auswerten und als fertigen Text für das Mitarbeitergespräch kopieren

Technik: eine Datei (`index.html`), Daten und Login in Supabase (bestehendes Projekt, Row Level Security:
jedes Konto sieht nur seine eigenen Daten). `config.js` enthält nur den öffentlichen Publishable Key.
Vercel veröffentlicht jede Änderung auf `main` automatisch.
