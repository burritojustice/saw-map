# saw-map
maps for SAW

If you generate a new GeoJSON file, just change the url in the `west_valley` scene section in the `.yaml` file.

To make a new layer, just make sure you filter it using a property and/or value. (Also, best to use the `_layer` convention in case you ever want to overlay on an existing basemap style.)

## Issues

Not familiar with OSMtoGeoJSON but these seem like converstion artifacts:
- highways look choppy
- islands don't seem to be polygons

## Dependencies

Leaflet: https://leafletjs.com/reference-1.7.1.html

Tangram: https://tangrams.readthedocs.io/en/latest/

OSMtoGeoJSON: https://tyrasd.github.io/osmtogeojson/
