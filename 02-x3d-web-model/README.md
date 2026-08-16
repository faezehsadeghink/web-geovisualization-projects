# Interactive X3D Web GIS Viewer

نمایش تعاملی یک مدل سه‌بعدی X3D در مرورگر با قابلیت تغییر زاویه دوربین و مشاهده مختصات مدل.

## Features
- External X3D model loading
- Default, top-down, and front viewpoints
- Interactive X/Y/Z coordinate inspection
- Attribute panel for selected objects
- Responsive browser interface

## Stack
HTML, CSS, JavaScript, X3D, X3DOM

## Run
From the repository root, run `python -m http.server 8000`, then open `/02-x3d-web-model/`. Opening the HTML file directly may prevent the external model from loading correctly.

## Files
- `index.html` — viewer interface
- `models/3model.x3d` — model loaded by the viewer
- `models/new-york-city.x3d` — additional source model
- `assets/` — model textures
