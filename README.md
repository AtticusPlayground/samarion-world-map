# Samarion Codex — World Map

Interactive world map for the Samarion Codex Pathfinder campaign
([samarioncodex.neocities.org](https://samarioncodex.neocities.org/)).
Base cartography from the community [pf-wikis mapping project](https://github.com/pf-wikis/mapping),
with the campaign's own era (277 AR) drawn on top: House Samarion's Taldor, the goblin
nation of Monster, restored Osirion and its vassals, the Kelesh Empire with Qadira
absorbed, and campaign landmarks.

Everything is static — GitHub Pages serves it as-is.

## Contents

- `index.html` — the map page (MapLibre GL + PMTiles, no build step)
- `golarion-innersea.pmtiles` — Inner Sea region vector tiles, extracted from the
  pf-wikis project's published archive (`pmtiles extract --bbox=-36,5,20,62`)
- `campaign-borders.geojson` / `campaign-locations.geojson` — the campaign era layer;
  edit these to change borders and landmarks (plain GeoJSON, lon/lat)
- `sprites/`, `fonts/` — map icons and glyphs from the pf-wikis project
- `vendor/` — maplibre-gl 6.2.0 and pmtiles 4.4.1, self-hosted

## Licensing

This project uses trademarks and/or copyrights owned by Paizo Inc., used under Paizo's
[Community Use Policy](https://paizo.com/licenses/communityuse). We are expressly
prohibited from charging you to use or access this content. This project is not
published, endorsed, or specifically approved by Paizo.

Base map data derives from the [pf-wikis mapping project](https://github.com/pf-wikis/mapping)
and its contributors — see their
[acknowledgments](https://github.com/pf-wikis/mapping#acknowledgments), including GIS
data first compiled by John Mechalas. Campaign-layer content is homebrew for the
Samarion Codex campaign.
