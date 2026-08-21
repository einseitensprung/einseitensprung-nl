# Einseitensprung Newsletter

Ein handgebauter Onepager, der den Look von [einseitensprung.at/newsletter](https://einseitensprung.at/newsletter/) übernimmt: das Archiv aller Newsletter-Ausgaben als Pill-Links im Hero, dazu eine Siegel-Reihe mit den echten Qualitätsmerkmalen des Originals (WCAG AAA, DSGVO-konform, handgefertigt mit AI-Unterstützung).

**🔗 Live-Preview:** https://einseitensprung.github.io/einseitensprung-nl/

## Design

- **Farben** — helles Blau-Theme (`#1c72b8` / `#2ea8e6`), plus die Tag-Akzentfarben als Kategorie-Coding
- **Typografie** — Josefin Sans (Display) + Inconsolata (Fließtext), das originale Font-Pairing des Blogs, bewusst als durchgängiger Terminal-/Code-Look übernommen; beide Fonts selbst gehostet statt von Google geladen
- **Struktur** — die Newsletter-Ausgaben als Pill-Links direkt im Hero, keine Timeline
- **Barrierefreiheit** — sichtbare Fokus-States, `prefers-reduced-motion` respektiert, Light-/Dark-Mode über CSS-Tokens

## Struktur

```
index.html          – Markup (Newsletter-Archiv)
assets/style.css     – Styles
assets/script.js     – Menü-Interaktion
assets/fonts/         – selbst gehostete Josefin-Sans-/Inconsolata-Woff2s
```

Keine Build-Schritte, keine Bundler — die Dateien werden direkt verlinkt.

## Lokal ansehen

```bash
# einfach im Browser öffnen
open index.html   # macOS
start index.html  # Windows
```

Kein Build, kein Backend, keine externen Abhängigkeiten — auch die Fonts sind selbst gehostet (`assets/fonts/`), es wird nichts von Google nachgeladen.

## Hinweis

Dies ist ein inoffizieller Fan-Onepager basierend auf öffentlich einsehbaren Inhalten von einseitensprung.at/newsletter. Für die Hauptseite und den Kontakt siehe das Original.
