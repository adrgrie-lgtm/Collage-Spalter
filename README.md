# Collage-Spalter

Macht Einzelbilder aus Collagen – komplett lokal im Browser. Zusatz-Tool zur [VideoSchmiede](https://github.com/adrgrie-lgtm/Videoschmiede).

## Was es tut

- **Collage reinziehen** (JPG/PNG/WEBP): ein Bild mit mehreren Panels – Comic-Collage, Foto-Grid …
- **Raster festlegen:** Spalten × Reihen (z. B. 6 × 4 für 24 Panels)
- **Rand abschneiden:** 0–12 % pro Seite – weiße Stege verschwinden
- **Panels an-/abwählen:** per Klick auf die Vorschau; für unregelmäßige Collagen einfach überzählige Zellen deaktivieren
- **Speichern als JPG:** Original-Pixelgröße, 92 % Qualität, zeilenweise nummeriert in Lesereihenfolge: `name_panel-01.jpg`, `name_panel-02.jpg` …

## Workflow

1. `index.html` öffnen und Collage reinziehen oder anklicken.
2. Spalten × Reihen und Rand-Anteil wählen, „Raster anwenden“.
3. Überflüssige Panels per Klick abwählen (dunkel = wird nicht gespeichert).
4. „Panels als JPG speichern“ – der Browser fragt evtl. einmal nach Erlaubnis für mehrere Downloads, mit OK bestätigen.
5. Einzelbilder in die [VideoSchmiede](https://github.com/adrgrie-lgtm/Videoschmiede) ziehen – jedes Bild wird eine Filmszene.

Kein Server, kein Upload, kein Konto, kein Tracking – alles läuft lokal im Browser.
