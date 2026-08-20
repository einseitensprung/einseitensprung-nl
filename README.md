# Einseitensprung Blog

Ein handgebauter Onepager, der den Look und die Themen von [einseitensprung.at/blog](https://einseitensprung.at/blog/) auf eine einzige Seite destilliert: ein Blog-Feed der letzten Posts, eine `whoami`-Sektion und eine Siegel-Reihe mit den echten Qualitätsmerkmalen des Original-Blogs (WCAG AAA, DSGVO-konform, cookie-frei, handgefertigt).

**🔗 Live-Preview:** https://einseitensprung.github.io/einseitensprung-nl/

## Design

- **Farben** — helles Blau-Theme (`#1c72b8` / `#2ea8e6`) statt des Original-Plum/Magenta, plus die Tag-Akzentfarben als Kategorie-Coding
- **Typografie** — Josefin Sans (Display) + Inconsolata (Fließtext), das originale Font-Pairing des Blogs, bewusst als durchgängiger Terminal-/Code-Look übernommen
- **Struktur** — ein Blog-Feed im Git-Log-Stil: eine Datumsschiene mit farbcodierten Knoten statt generischer Nummerierung, dazu Tag-Chips pro Eintrag
- **Barrierefreiheit** — sichtbare Fokus-States, `prefers-reduced-motion` respektiert, Light-/Dark-Mode über CSS-Tokens

## Struktur

```
index.html          – Markup (Blog-Übersicht)
detail.html          – Markup (einzelner Blog-Beitrag)
newsletter.html       – Markup (Newsletter-Archiv)
assets/style.css     – Styles
assets/script.js     – Pagination-, Such- und Menü-Interaktion
```

Keine Build-Schritte, keine Bundler — die Dateien werden direkt verlinkt.

## Lokal ansehen

```bash
# einfach im Browser öffnen
open index.html   # macOS
start index.html  # Windows
```

Kein Build, kein Backend, keine Abhängigkeiten außer den Google-Fonts-Links.

## Hinweis

Dies ist ein inoffizieller Fan-Onepager basierend auf öffentlich einsehbaren Inhalten von einseitensprung.at/blog. Für den vollständigen Blog, Kontakt und Newsletter siehe das Original.
