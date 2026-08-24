# Mapping with Kids

A small GIS course for kids, built around [GeoLibre](https://geolibre.app), a
free and open-source web GIS tool.

**Live site:** https://soniadas123.github.io/mapping-with-kids/

## What's here

- `index.html` — the cover page, linking to both PDFs below.
- `Remote_Sensing_and_GIS_Intro.pdf` — a short intro to remote sensing,
  satellites, and GIS, meant to be read before Exercise 1.
- `exercise1/` — Exercise 1: building a map of India.
  - `Map_of_India_Tutorial.pdf` — the step-by-step tutorial.
  - `data/` — the GeoJSON boundary data used in the exercise (the large
    `.geojson` files are not tracked in this repo; see below).
  - `screenshot/` — reference screenshots from the exercise.

## Note on large files

A few large working files are intentionally excluded from this repo (see
`.gitignore`) since they aren't needed to view the tutorials:
`exercise1/screenshot/exercise1.html`, `exercise1/screenshot/exercise1.geolibre.json`,
and the raw `.geojson` boundary data in `exercise1/data/`. Those stay on the
original working machine.
