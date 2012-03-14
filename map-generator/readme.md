The process of generating the map svg:

1. generate-map-sources.py will generate a set of yaml configuration files (map sources). this will include the world map plus one map for each country. if possible this step will also try to match the naturalearth regions to the geoip adm1 regions.
2. the auto-generated map sources may now be manually changed to adopt special cases in certain countries
3. generate-maps.py will load the map sources and use kartograph to render all svg maps.
