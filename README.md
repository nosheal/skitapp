# SkiTap

A daily geography game for ski resorts. Five rounds: each names a resort somewhere on Earth, you spin the 3D globe and tap where you think it is. Scored out of 100.

**Play:** https://nosheal.github.io/skitapp

## What's in it

- 63 curated resorts across six continents
- 3D globe (MapLibre GL JS globe projection)
- Real elevation hillshade — Mapzen Terrarium DEM tiles, snow-white highlights
- Mountain photo for each resort fetched live from the Wikipedia `pageimages` API
- Great-circle distance scoring, Wordle-style share emoji

## Tech

Single static HTML file. MapLibre GL JS 5.5 via CDN. No build step.

## Data sources

- Resort coordinates: hand-curated from public references
- Elevation: [Mapzen Terrarium tiles](https://registry.opendata.aws/terrain-tiles/) (AWS Open Data)
- Basemap: CartoDB Dark Matter (OpenStreetMap data)
- Resort photos: [Wikipedia / Wikimedia Commons](https://en.wikipedia.org/) via MediaWiki API
