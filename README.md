All Shapefile can be coverted to Geojson.

1.United States Census Bureau
http://www.census.gov/geo/maps-data/data/tiger-line.html

2.Natural Earth 
http://www.naturalearthdata.com/downloads/

That means we can use tons of open source geographical data online to draw any map we want.

3.GDAL - Geospatial Data Abstraction Library provide transfer tool: ogr2ogr covert .shp to .json
command line: ogr2ogr -f "GeoJSON" output.json filename.shap

4.http://mapshaper.org/ 
is an excellent tool to simplify big shapefiles and jsonfiles.

5. we can use any prjection setted in d3
https://github.com/d3/d3-geo-projection

6. http://www.gpsvisualizer.com/geocoder/
the input can be zipcode or county name, or address, the output will be longitude and latitude. That mean we can draw it on map directly.

