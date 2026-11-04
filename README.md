# Collage-Spalter

Macht Einzelbilder aus Collagen – komplett lokal im Browser. Zusatz-Tool zur [VideoSchmiede](https://github.com/adrgrie-lgtm/Videoschmiede).

## Was es tut

- **Collage reinziehen** (JPG/PNG/WEBP): ein Bild mit mehreren Panels – Comic-Collage, Foto-Grid …
- **Raster-Modus:** Spalten × Reihen (bis 12 × 12), Rand je Panel (0–8 %) – weiße Stege verschwinden. Panels per Klick an-/abwählen.
- **Bereich abschneiden:** Titel- oder Fußzeilen (oben/unten) und Seitenränder (links/rechts) in Prozent entfernen, bevor das Raster gelegt wird – z. B. Comics mit Titelzeile: „oben“ auf ca. 10 %.
- **Freies Zuschneiden (Neu):** für unregelmäßige Comics und Collagen – jedes Panel mit gedrückter Maustaste als Rechteck aufziehen, Aufzieh-Reihenfolge = Nummerierung, Klick auf ein Panel entfernt es.
- **Speichern als JPG:** Original-Pixelgröße, 92 % Qualität, nummeriert: `name_panel-01.jpg`, `name_panel-02.jpg` …

## Workflow

1. `index.html` öffnen und Collage reinziehen oder anklicken.
2. Modus wählen: Raster (regelmäßige Grids) oder Freies Zuschneiden (unregelmäßige Layouts).
3. Raster: Spalten × Reihen + Bereich/Ränder einstellen, „Raster anwenden“, überflüssige Panels abwählen. Frei: Panels der Reihe nach aufziehen.
4. „Panels als JPG speichern“ – der Browser fragt evtl. einmal nach Erlaubnis für mehrere Downloads, mit OK bestätigen.
5. Einzelbilder in die [VideoSchmiede](https://github.com/adrgrie-lgtm/Videoschmiede) ziehen – jedes Bild wird eine Filmszene.

Kein Server, kein Upload, kein Konto, kein Tracking – alles läuft lokal im Browser.
