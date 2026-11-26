# RemoPad Screens

Fertige Screens für die iPhone-App [RemoPad](https://remopad.pages.dev). Die App zeigt diesen Katalog unter
Einstellungen › Screens › „Screen-Katalog“, lädt ihn nur auf Antippen und speichert einen Screen erst nach „Hinzufügen“.

Ready-made screens for the [RemoPad](https://remopad.pages.dev) iPhone app (Settings › Screens › "Screen catalog").

- `index.json` – Katalogindex (`ScreenCatalog`-Format); jede Datei ist per SHA-256 und Größe an einen Commit gebunden.
- `screens/<slug>/` – `<slug>.remopadscreen`, `meta.json` und Vorschaubilder `preview-*.png`.
- `tools/accepted-risks.json` – vom Maintainer freigegebene Tastenkombinationen, an den Hash der Datei gebunden.

Die Dateien enthalten nur Daten (Tasten, feste Aktionen, Beschriftungen und Bilder als Pixeldaten), keinen Code. Erzeugt und geprüft mit
`remopad-screen-tool` (`generate`, `validate`, `build-index`).

Lizenz / License: alle Screens [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

Problem mit einem Screen? In der App „Melden“ oder E-Mail an info@habitfit.de.
