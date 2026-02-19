The New York City Office of Technology and Innovation Geographic Information Systems team maintains Building footprints. See this repository for details and some sketchy but current metadata.

https://github.com/mattyschell/geodatabase-buildings

This dataset includes small placeholder triangular building footprints that are marked, appropriately enough, with the feature code "placeholder" (feat_code=1003)  Most users will want to filter these triangles out of the building footprints before use.   

The Office of Technology and Innovation also maintains a dataset of historic building footprints where demolished buildings are interred.  Use care when using this dataset, it lacks strict constraints and quality assurance. It is intended for more fuzzy general  

### NYCMaps ArcGIS Online

Refreshed every weekend.

Building: https://nyc.maps.arcgis.com/home/item.html?id=870bf69e8a8044aea4488e564c0b4010

Building_Historic: https://nyc.maps.arcgis.com/home/item.html?id=780dd00c689f444cb20070185fada44d


### Open Data Portal: Building Footprints

The Geographic Information Systems team publishes a slightly processed version of their internal buildings data to the Open Data Portal weekly.

Building: https://data.cityofnewyork.us/Housing-Development/Building-Footprints/nqwf-w8eh

Building_Historic: https://data.cityofnewyork.us/Housing-Development/Building-Footprints-Historical-Shape/s5zg-yzea

### Microsoft's Computer-Generated Building Footprints

Microsoft released an ODBL-licensed nationwide building footprint dataset. 

https://github.com/Microsoft/USBuildingFootprints/

The format is GeoJSON and downloads are chunked by state.  To clip New York City and output a shapefile, ogr2ogr is always a solid option.

   `ogr2ogr -f "ESRI Shapefile" nyc.shp NewYork.json -clipsrc -74.3027914 40.4681991 -73.61703247 40.97574288`

### Fire Department: Building Footprints Database

The Fire Department of New York City maintains a similar internal, not public, database of building footprints.  It contains additional info like building plans that are critical to the Fire Department.


