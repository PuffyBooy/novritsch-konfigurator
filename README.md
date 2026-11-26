# SSR · SSG Konfigurator (Fanprojekt)

Inoffizieller 3D-Konfigurator für Novritsch-Airsoft-Gewehre (SSG11, SSG10 A3, SSG96 Mk2, SSR4 Mk1, SSR4 Mk2, SSR74, SSQ4, SSR9 DSG) im Stil eines Auto-Konfigurators:
Modell wählen, Optik, Mündung, Zweibein und Magazin Schritt für Schritt montieren, dann aus dem kompletten passenden Zubehör der jeweiligen „The … System“-Seite wählen (über 330 Produkte, Lampen, PEQ-Boxen und Griffe auch in 3D), am Ende Preisliste und Build-Code.

**Live:** https://puffybooy.github.io/novritsch-konfigurator/

## Inhalt
- `index.html` – die ganze Seite (three.js über jsDelivr)
- `*.json` – 3D-Modelle als glTF mit eingebettetem Puffer (große Modelle in Teile aufgeteilt)
- `card_*.jpg` – Bilder für die Modellauswahl
- `cat.json` + `cat_0…3.jpg` – Zubehör-Katalog je System (Name, Preis, Lieferstatus) und Vorschaubilder als Sprite

## Lokal testen
Die Seite lädt die Modelle per `fetch`, ein Doppelklick auf `index.html` reicht deshalb nicht:

```bash
python3 -m http.server 8000
# dann http://localhost:8000 öffnen
```

## Hinweis
Fanprojekt, nicht mit Novritsch verbunden. Die 3D-Modelle sind nach den öffentlichen Produktfotos von eu.novritsch.com nachgebaut (mit Erlaubnis). Preise sind Richtpreise aus dem EU-Shop, Stand 26.11.2026.
