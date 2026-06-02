# Hellas 2026, The Skedros / Lohse Family Journey

A cinematic preview of the family's June 6 to June 21, 2026 trip through Athens, Chios, and Crete.

Live site: `https://skedros.github.io/greece-journey/`

## Repository structure

```
greece-journey/
├── index.html      The slideshow (single file, ~62 KB)
├── .nojekyll       Tells GitHub Pages to serve files as-is
├── README.md       This file
└── images/         18 background images (you provide these)
    ├── cape-sounion.jpg
    ├── acropolis.jpg
    └── ...
```

## Hosting on GitHub Pages

1. Create a new public repo, suggested name: `greece-journey`
2. Upload everything in this folder plus your `images/` directory containing 18 JPGs
3. Go to Settings → Pages, set:
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`
4. Wait about 60 seconds, then visit `https://YOUR-USERNAME.github.io/greece-journey/`

## Required images

Drop these 18 JPG files into an `images/` folder next to `index.html`. Filenames must match exactly. Suggested dimensions: landscape orientation, around 1200 to 1600 pixels wide.

| Filename                  | Used on                             |
|---------------------------|-------------------------------------|
| `cape-sounion.jpg`        | Title card                          |
| `acropolis.jpg`           | Athens chapter hero                 |
| `anafiotika.jpg`          | Athens stay slide + Athens gallery  |
| `temple-zeus.jpg`         | Athens quote                        |
| `plaka.jpg`               | Athens return + Athens gallery      |
| `lycabettus.jpg`          | Finale + Athens gallery             |
| `monastiraki.jpg`         | Athens gallery                      |
| `hadrians-library.jpg`    | Athens gallery                      |
| `pyrgi.jpg`               | Chios chapter hero + Chios gallery  |
| `nea-moni.jpg`            | Chios stay + Chios gallery          |
| `chios-harbor.jpg`        | Chios quote + Chios gallery         |
| `mesta.jpg`               | Chios gallery                       |
| `chios-landscape.jpg`     | Chios gallery                       |
| `chania-harbor.jpg`       | Crete chapter hero + Crete gallery  |
| `samaria-gorge.jpg`       | Crete stay + Crete gallery          |
| `balos-lagoon.jpg`        | Crete quote + Crete gallery         |
| `elafonisi.jpg`           | Crete gallery                       |
| `chania-old-town.jpg`     | Crete gallery                       |

If any image is missing, that slide gracefully falls back to a deep-navy and terracotta gradient. No errors.

## What's in the slideshow

20 slides total, in order:

1. Intro with Greek letter reveal (ΕΛΛΑΣ)
2. Title card with countdown to takeoff
3. The Skedros / Lohse family slide with all 12 traveler names
4. Animated route map of the Aegean
5. Athens chapter hero
6. Athens stay (Alke Homme)
7. Athens quote
8. Athens gallery, 5 photos
9. Map interlude (Athens to Chios)
10. Chios chapter hero
11. Chios stay (Grecian Castle)
12. Chios quote
13. Chios gallery, 5 photos
14. Map interlude (Chios to Chania)
15. Crete chapter hero
16. Crete stay (Villa Dioni and Agioi Apostoloi)
17. Crete quote
18. Crete gallery, 5 photos
19. Athens return chapter
20. Finale with stats and back-link to the trip site

## Controls

- Click anywhere or press → to advance
- Press ← to go back
- Swipe left/right on touch devices
- Click a dot at the bottom to jump to any slide
- Press Home to restart, End to jump to the finale

## Credits

Built with HTML, CSS, JavaScript. Fonts: Fraunces and Inter via Google Fonts. No external JS libraries.
