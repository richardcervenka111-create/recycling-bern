# Recycling Bern

Die Entsorgung-App sagt, wann der Kehricht kommt. Sie sagt nicht, wo die nächste Glassammelstelle ist, wenn du gerade mit vollen Händen vor der Tür stehst.

Live: **https://richardcervenka111-create.github.io/recycling-bern/**

Drei Sprachen (DE/EN/SK), „nächster Punkt“ mit Fussroute, kein Tracking, Standort bleibt im Gerät.

## Daten

Recycling-Sammelstellen der Stadt Bern aus OpenStreetMap mit den erfassten Fraktionen (recycling:*=yes). Ergänzt die Entsorgung-App der Stadt, die Abfuhrtermine kennt, aber nicht die nächste Sammelstelle.

`data.js`: 175 Punkte, OpenStreetMap-Stand 2026-09-24T23:25:06Z, gebaut am 2026-09-25 mit `_tools/make_map_app.py` (Overpass API, Bounding Box Stadt Bern 46.90–46.99 / 7.37–7.50). Lizenz ODbL, © OpenStreetMap-Beitragende. Karte: OSM-Kacheln, Leaflet 1.9.4 (cdnjs, mit Integritätsprüfung).

## Ehrlich gesagt

OpenStreetMap ist so gut wie die Leute, die es pflegen. Fehlt ein Punkt oder stimmt ein Detail nicht: in OpenStreetMap korrigieren, davon haben alle etwas. Diese Seite ersetzt keine offizielle Auskunft der Stadt.

## Lokal

`index.html` im Browser öffnen. Kein Build.

## Lizenz

Code MIT. Daten ODbL (OpenStreetMap).
