# 2D Web Map with GeoServer and OpenLayers

یک نمایشگر Web GIS دوبعدی برای نمایش لایه‌های WMS، تغییر نقشه پایه، شناسایی عوارض و ترسیم هندسه‌ها.

## Features
- OpenStreetMap and Esri World Imagery basemaps
- GeoServer WMS layer catalogue
- Feature information queries
- Point, line, and polygon drawing tools
- Persian right-to-left interface

## Stack
HTML, CSS, JavaScript, OpenLayers 8.2, Proj4js, GeoServer WMS

## Run
1. Start GeoServer on port `8081`.
2. Verify the workspace and layer names in `index.html`.
3. From the repository root, run `python -m http.server 8000`.
4. Open `/01-2d-web-map/`.

> The public page can display online basemaps, but local WMS layers require the configured GeoServer.
