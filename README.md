# Sustainability Map ![Frontend Status](https://github.com/OSU-Sustainability-Office/sustainability_map/actions/workflows/gh-deploy.yml/badge.svg)![Test Build Status](https://github.com/OSU-Sustainability-Office/sustainability_map/actions/workflows/test-workflow.yml/badge.svg)

An interactive map showing the sustainability features available at Oregon State University's Corvallis campus!

## Installation Steps

- Clone the repo
- Use nvm to get node version 18 (```nvm install 16 && nvm use 18```)
- ```npm install```
- ```npm run serve``` to test-run the website


## Notes about the build process:

The source code (under `src`) gets automatically bundled by vue-cli (which uses webpack) into compact static assets under `public`, additional static assets dependent on outside sources (e.g. OSU building geometry from Open Street Maps) get created before the vue-cli webpack build via scripts under the `util` directory.

## Helpful References for Development

- [Hjson Reference](https://hjson.github.io/)
- [BBox Tool](http://norbertrenner.de/osm/bbox.html)
- [OSU Rainwater Brohcure](https://fa.oregonstate.edu/sites/fa.oregonstate.edu/files/2021-07/stormwater_brochure_v12.pdf)
- [OSU Sustainability Office Website](https://fa.oregonstate.edu/sustainability/about)
- [OSU Sustainability Office Ecologue](https://blogs.oregonstate.edu/ecologue/)
- [Overpass Turbo](https://overpass-turbo.eu/#)
- [Overpass API](https://dev.overpass-api.de/overpass-doc/en/)
- [OpenStreetMap](https://www.openstreetmap.org/#map=15/44.5649/-123.2782)
- [GeoJSON specification](https://datatracker.ietf.org/doc/html/rfc7946)
- [Leaflet GeoJSON Features](https://leafletjs.com/examples/geojson/)
- [Leaflet Quickstart Guide](https://leafletjs.com/examples/quick-start/)
- [Official Leaflet Docs](https://leafletjs.com/reference-1.6.0.html)
- [Vue2Leaflet GitHub Page](https://github.com/vue-leaflet/Vue2Leaflet)
- [Vue2Leaflet Docs](https://vue2-leaflet.netlify.app/quickstart/#accessing-leaflet-api)
- [Vuex Store Docs](https://vuex.vuejs.org/)
