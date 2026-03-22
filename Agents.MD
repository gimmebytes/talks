# Talks Repository — gimmebytes

Dieses Repository enthält Conference Talks, Workshops und Präsentationen von Marvin Kruse (gimmebytes).

Deployed als GitHub Pages unter `talks.gimmebytes.com`.

## Folder-Layout

```
/
├── index.html                          ← Einstiegsseite (Kachel-Übersicht aller Talks)
├── CNAME                               ← Custom Domain für GitHub Pages
├── YYYY-MM-talk-slug/                  ← Ein Talk pro Ordner
│   ├── index.html                      ← Reveal.js Präsentation
│   ├── style.css                       ← Talk-spezifisches Styling
│   ├── dist/                           ← Reveal.js Core
│   ├── plugin/                         ← Reveal.js Plugins
│   └── images/                         ← Talk-spezifische Bilder
```

## Konventionen

- **Talk-Ordner:** `YYYY-MM-talk-slug` (z.B. `2026-03-kiro-made-me-do-it`)
- **Slide-Engine:** Reveal.js (lokal gebundled, kein CDN)
- **Design:** Dunkles Theme, Card-basiertes Layout (siehe bestehende Talks als Referenz)
- **Einstiegsseite:** Kachel-Ansicht mit Titel, Datum, Konferenz und Format-Tag (Slides/PDF)
- **PDFs:** Alte Talks können als PDF im jeweiligen Talk-Ordner liegen und von der Einstiegsseite verlinkt werden

## Slide-Richtlinien

- Maximum 5 Bullets pro Slide (exklusive Überschriften)
- Problem → Impact/Lösung auf zwei Folien trennen
- Zeitrahmen pro Talk beachten (typisch 30-45 Min)

## Öffentliches Repo

Dieses Repo ist öffentlich. Keine internen Firmendaten, keine API-Keys, keine Screenshots interner Systeme.

## Kontext

- Speaker: Marvin Kruse, Technical Lead bei OTTO
- Brand: gimmebytes ("Gib mir Bytes, ich mach was draus")
- Blog (geplant): gimmebytes.com (Chirpy/Jekyll, separates Repo)
- Talks: talks.gimmebytes.com (dieses Repo)
