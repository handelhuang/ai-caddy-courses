# AI Caddy course packs

Course data used by the AI Caddy iPhone app: hole geometry, elevation grids and tree cover, built automatically from open data and served as static files.

- `index.json` lists every built course.
- `packs/<course>/` holds a course's manifest and per-hole files.
- To ask for a course, open an issue with the `course-request` label (the app does this for you).

## Data sources and licences

- Map data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, available under the [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/). The course packs in this repository are a derived database and are shared under the same licence.
- Elevation: [USGS 3DEP](https://www.usgs.gov/3d-elevation-program) (public domain).
- Tree cover: Meta and World Resources Institute, [High Resolution Canopy Height Maps](https://registry.opendata.aws/dataforgood-fb-forests/), CC BY 4.0.

Improving a course's map in OpenStreetMap (holes, greens, bunkers, water) improves the pack the next time it is built.
