Municipal Spatial Data
====

This Repository will contain the spatial data of all the Municipalities that has been scraped from their websites and other sources.

Do note, that the wards in these datasets, are usually the Municipal wards, and not the Census wards.

====

**Note on the Formats**

Most lay people will be interested in KMLs, and web Developers in GeoJSON. So I'm trying to focus on these 2 formats. A couple of other advantages of these formats,is that they can be diffed in Git, and GeoJSON is shown on a Map by Github, so it's a win for all. 

In the GIS industry, Shapefiles are the defacto Standard Format, but it also sufferes from several issues. This is why I have decided not to keep Shapefiles in this Repo. Those who need shapefiles, can always convert these formats to Shapefile, using something like GDAL. This can be achieved by something as simple as the following command:

`ogr2ogr output.shp input.geojson`

If you need to view them in a Desktop GIS, I'll recommend QGis

====

**License**

The dataset shared under [Creative Commons Attribution-ShareAlike 2.5 India](http://creativecommons.org/licenses/by-sa/2.5/in/) license.
