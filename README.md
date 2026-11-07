# 🎯 Dartzähler

Ein X01-Dartzähler (301 / 501 / 701) als **eine einzelne HTML-Datei** – ohne externe Bibliotheken, komplett offline, für Smartphones im Hochformat gemacht.

## Funktionen
- Eingabe über eine antippbare SVG-Dartscheibe (Single innen und außen, Double, Triple, 25, Bull) und einen Button „Daneben“
- Scheibe zoombar: mit zwei Fingern zoomen, mit einem Finger verschieben, oder über die Buttons − / + / ⤢ oben; die Zahlen wandern beim Zoomen mit und bleiben immer am Rand sichtbar
- Alternativ Zifferneingabe (Schalter im Startbildschirm oder 🔢/🎯-Button im Spiel): Single/Double/Triple wählen, dann Zahl 1–20, 25 oder Bull
- Nach drei Darts (oder Bust) wird die Aufnahme angezeigt; erst mit „Weiter“ ist der nächste Spieler dran
- Double In / Double Out, Bust-Regel, Legs und Sets (Best of …)
- Checkout-Vorschläge (≤ 170 bei Double Out)
- Rückgängig-Funktion für jeden Dart, auch über Spielerwechsel hinweg
- Statistik: 3-Dart-Durchschnitt, Darts, letzte Aufnahme, Höchstwert, 180er, bestes Checkout
- Der Spielstand wird automatisch gespeichert (localStorage), die Spieler werden gemerkt

## Öffnen auf dem Handy
**Variante A – nur die Datei:** `index.html` aufs Handy kopieren (USB, Cloud, Mail) und mit Chrome/Firefox öffnen (Android: Dateimanager → Öffnen mit → Chrome).

**Variante B – als App mit Homescreen-Icon (PWA):** Das Repository über GitHub Pages veröffentlichen
(Settings → Pages → Branch auswählen), die URL im Handy-Browser öffnen und dann
„Zum Startbildschirm hinzufügen“ wählen (Android/Chrome: Menü ⋮; iPhone/Safari: Teilen-Symbol). Danach läuft die App auch offline.

`manifest.webmanifest`, `sw.js` und die Icons sind optional und werden nur für Variante B gebraucht.
