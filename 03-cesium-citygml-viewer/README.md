# CityGML to 3D Tiles — Cesium Viewer

تبدیل داده CityGML در FME، سازگارکردن سیستم مختصات و نمایش خروجی OGC 3D Tiles در CesiumJS.

## Workflow
`CityGML → FME reprojection and conversion → OGC 3D Tiles → CesiumJS`

## Features
- ArcGIS World Imagery basemap
- Local 3D Tiles loading
- Automatic camera flight to the model
- Live longitude, latitude, and height display
- 3D feature identification and attribute display
- Point and line drawing tools

## Stack
CityGML, FME, OGC 3D Tiles, CesiumJS 1.107.1, HTML, CSS, JavaScript

## Run
From the repository root, run `python -m http.server 8000`, then open `/03-cesium-citygml-viewer/`. A web server is required because the viewer fetches `tileset.json` and binary tile content.
