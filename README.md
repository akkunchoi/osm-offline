offline open street map

1. Export osm data from https://www.openstreetmap.org/export#map=15/34.6973/135.4915 and save it as "map.osm"
2. install Geo::OSM::Tiles (from cpan)
3. Run `perl Geo-OSM-Tiles-0.02/downloadosmtiles.pl --lat=34.6944:34.7090 --lon=135.4820:135.5102 --zoom=13:20`


