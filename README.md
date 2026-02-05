# GEOG 458 Lab 4

This project demonstrates the creation and use of four different XYZ tile sets that were generated in QGIS and displayed on a web map using Mapbox GL JS and GitHub Pages.

The goal of the lab was to practice exporting map layers as web tiles, organizing them correctly, and integrating them into a simple interactive map with a layer switcher.

---

## Tile Sets Overview

### Tile Set 1 — Basemap
- Represents a basic basemap style inspired by Mapbox Streets.
- Exported from QGIS using the Generate XYZ Tiles tool.
- Serves as a reference background layer.

### Tile Set 2 — Thematic Layer
- Displays a thematic dataset (public data) without a basemap. But I was having issues with my dataset that I used.
- Styled in QGIS prior to export.

### Tile Set 3 — Basemap + Thematic
- Combines the basemap with an overlaid thematic layer from tileset2.
- Exported as a single XYZ tile set to preserve styling consistency.
- Demonstrates how multiple layers can be merged into one tiled output.

### Tile Set 4 — Themed Map Design
- A fully styled thematic map created in QGIS.
- Emphasizes nature to go with my dataset that focused on Seattle parks.
- Exported as XYZ tiles for use on the web.

---

## Tools Used

- **QGIS** — Data preparation, styling, and XYZ tile generation
- **Generate XYZ Tiles (Directory)** tool in QGIS
- **GitHub Pages** — used for hosting the web map
- **Mapbox GL JS** — Map rendering and layer switching
- **HTML / CSS / JavaScript** — Basic web map structure

---

## Project Structure


Each `tileset_*` directory contains XYZ tiles organized by zoom level following the standard `{z}/{x}/{y}.png` structure.

---

## Live Map

The project is hosted using GitHub Pages and can be viewed at:

https://206et.github.io/geog458-lab4/

---

## Notes

- All tile sets were generated directly from the QGIS map canvas using consistent extents and zoom levels.
- The layer switcher allows users to toggle between the four tile sets to compare different map designs and data representations.
- This project focuses on workflow and structure rather than advanced interactivity.

---

## Author

Emmanual Tadesse
GEOG 458
