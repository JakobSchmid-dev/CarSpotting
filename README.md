# Motorworld Spotting

Handy-App zum Zählen gesichteter Autos, mit Favoriten und eigenen Fotos. Die App ist eine einzige HTML-Seite und lässt sich als Web-App (PWA) auf dem Home-Bildschirm installieren. Sie läuft auch offline.

## Online stellen (GitHub Pages)

1. Auf GitHub: **Settings → Pages**.
2. Unter „Build and deployment“ bei **Source** „Deploy from a branch“ wählen.
3. Den Branch mit dieser App auswählen, den Ordner `/ (root)` lassen und speichern.
4. Nach etwa einer Minute steht oben die Adresse, z. B. `https://<name>.github.io/CarSpotting/`.

GitHub Pages ist bei privaten Repos nur mit GitHub Pro verfügbar. Ohne Pro muss das Repo öffentlich sein.

## Auf dem Handy installieren

- **iPhone (Safari):** Adresse öffnen → Teilen-Knopf → „Zum Home-Bildschirm“.
- **Android (Chrome):** Adresse öffnen → Menü ⋮ → „App installieren“ bzw. „Zum Startbildschirm hinzufügen“.

## Wo die Daten liegen

Zähler, Favoriten und Fotos werden auf dem Handy selbst gespeichert (localStorage und IndexedDB). Es gibt keinen Server. Wenn du die App löschst oder die Website-Daten im Browser löschst, sind die Daten weg.
