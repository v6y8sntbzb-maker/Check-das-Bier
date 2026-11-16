# Check das Bier – Brauhauskarte Deutschland

Eigenständige mobile Web-App (PWA) für iPhone und Desktop.

## Funktionen
- Deutschlandkarte auf Basis von OpenStreetMap / Leaflet
- Suche nach Brauerei, Ort und Adresse
- Filter für Ausschank-Markierung und Bundesland
- Favoriten lokal im Browser
- Standort-Zentrierung und Routenlink
- Installation über Safari: Teilen → Zum Home-Bildschirm

## GitHub Pages
In Repository Settings → Pages → Deploy from a branch → Branch `main`, Ordner `/(root)` wählen. Danach die veröffentlichte Adresse in Safari öffnen.

## Datenqualität
Die App fragt OpenStreetMap über Overpass ab. Die Daten sind gemeinschaftlich gepflegt und nicht amtlich vollständig. Einträge mit Pub-/Biergarten-/Restaurant-Kennzeichnung und Brauerei-Bezug werden als „Ausschank markiert“ angezeigt; reine Brauerei-Einträge als „Ausschank prüfen“. Öffnungszeiten und tatsächlichen Ausschank bitte vor dem Besuch prüfen.

Favoriten werden lokal gespeichert. Der Standort wird nur nach Betätigung des Standort-Buttons abgefragt.
