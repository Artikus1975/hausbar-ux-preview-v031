# HausbarNext UX Preview v0.32

Private non-productive UX/UI/accessibility preview branch.

# Hausbar Next v0.24

Korrektur nach v0.18: Die Datenanreicherung bleibt erhalten, aber die sichtbaren Inventar-Filter werden wieder auf kontrollierte, nutzerfreundliche Facetten begrenzt.

## Zweck dieser Version

- keine ausufernden Geschmacksfilter wie einzelne Botanicals, Früchte oder Detailnoten
- keine ausufernden Nutzungs- und Stilfilter
- Herkunftsfilter zeigt nur noch die Haupt-Herkunft, nicht Regionen/Orte/Dörfer
- detaillierte Tags bleiben intern für Suche, Beschreibung und spätere Intelligenz erhalten
- Inventar bleibt übersichtlich für den Nutzer

## Nicht geändert

- keine Änderung an der Grundlogik der App
- keine Änderung am Rauchig-Prinzip
- keine UI-Experimente
- keine neuen Daten-Enrichment-Batches
- keine Runtime-Hooks, keine Wrapper, kein Service Worker

## Upload

Die fünf App-Dateien ersetzen:

- index.html
- style.css
- app.js
- data.js
- README.md

Testlink:

https://artikus1975.github.io/HausbarNext/?v=019


## v0.21

Controlled Inventory Filter Taxonomy: sichtbare Inventarfilter sind auf kuratierte Hauptwerte begrenzt. Interne Detailtags bleiben erhalten, erscheinen aber nicht als Filteroptionen. Herkunftsfilter zeigt nur Länder.


## v0.21

- Inventar-Flaschendetails zeigen den Bereich „Servieren“ nicht mehr an.
- Servierdaten bleiben intern in den Daten erhalten.
- Keine Änderung an Filtern, Rezepten, Tagescocktail oder Datenanreicherung.

## v0.24

Basis: v0.21. Repariert Home-Rezeptlinks robust und bereinigt die Rezeptdetailansicht ohne Inventar-, Filter- oder Datenmigration.

Für GitHub Pages nur den Inhalt aus `app/` hochladen. `archive/` ist reine Dokumentation.


## v0.28 Season removal
- Season/Jahreszeit recipe field removed from legacy recipe runtime data.
- Season filter removed from recipe UI and app state/filter logic.
- Season removed from recipe cards, daily drink/menu labels, and recipe search indexing.
- Inventory descriptive text is unchanged; words such as “Sommerdrink” remain descriptive content, not Season functionality.


## v0.32 UX/UI iPhone patch preview
Private non-productive preview. Recipes are sourced from REZEPT_MASTER_PRIVAT_v2.90; inventory identity is sourced from v7.66. Season and Food Pairing are not app functions. B03 remains closed.
