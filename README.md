# Caseo – Website

Statische Website (nur HTML und CSS, kein Build nötig).

## Dateien
- `index.html` Startseite
- `ueber-uns.html` Unser Weg
- `partner.html` Partner (Familie Bertrams, Alnatura und weitere)
- `kaufen.html` Kaufen: die beiden Kits mit Bestell-Buttons
- `style.css` Gestaltung
- `images/` Bilder (Kasi und Fotos)

## Auf GitHub veröffentlichen (GitHub Pages)
1. Neues Repository auf github.com anlegen, z. B. `caseo`.
2. Alle Dateien aus diesem Ordner hochladen (Add file → Upload files).
3. Unter Settings → Pages bei „Source“ den Branch `main` und den Ordner `/ (root)` wählen und speichern.
4. Nach ein bis zwei Minuten ist die Seite unter `https://DEIN-NAME.github.io/caseo/` erreichbar.

## Noch auszufüllen
- `[E-MAIL-ADRESSE]` in `index.html`, `partner.html` und `kaufen.html`
- `[PREIS]` in `kaufen.html` (je Kit)
- `[LINKS EINTRAGEN]` für Impressum und Datenschutz in allen drei Seiten (in Deutschland Pflicht)
- `[WEITERER PARTNER]` in `partner.html`

## Schriften
Die Seite nutzt Systemschriften und lädt nichts von fremden Servern. Eigene Schriften (z. B. Fredoka und Nunito) kannst du selbst hosten und in `style.css` per `@font-face` einbinden.

## Kaufen-Seite
GitHub Pages kann keine Zahlungen abwickeln. Die Buttons öffnen deshalb eine E-Mail an dich. Für echtes Online-Bezahlen kannst du später einen Zahlungslink eines Anbieters (z. B. Stripe Payment Links oder PayPal) in die Buttons eintragen oder einen Shop-Dienst verlinken. Beim Verkauf in Deutschland brauchst du außerdem AGB, Widerrufsbelehrung und Preisangaben inkl. Versand. Für Kinderspielzeug gelten zudem Sicherheitsvorschriften, lass das vor dem Verkauf prüfen.
