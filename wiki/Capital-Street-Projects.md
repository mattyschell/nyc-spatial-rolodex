The New York City Department of Transportation maintains an inventory of major capital street construction projects as identified in the City's 10 year Capital Plan.  The Department of Transportation represents these projects spatially as two related datasets; streets (linear data) and intersections (point data).

The number of projects in the capital plan change frequently and the capital street construction projects file maintained internally at the Department of Transportation changes frequently to track these active projects.  At any given time the files appear to show projects with construction years dating from several years in the past up to approximately 10 years into the future.  The file name also appears to indicate the date of release. 

So for example as of October 2018 the Department of Transportation provides files named like "20181016_*.shp" with construction years ranging from 2005 up to 2027.

### Open Data Portal

https://data.cityofnewyork.us/Transportation/New-York-City-Street-Reconstruction-10-Year-Plan/dgm3-gggb

This dataset is rarely updated to match the current projects at the Department of Transportation.  As of 2015 the zip file yields a strange hierarchy of directories containing what appear to be identical shapefiles under different directory trees.

The streets dataset may include some linear collection features where a single record maps to multiple disconnected street segments.  Similarly the points layer may include some (or all) records that are point collections. Most users will want to explode these collections into individual records unless they are in to that type of anarchy.


### New York City Department of Transportation 

http://www.nyc.gov/html/dot/html/infrastructure/capital-projects.shtml

or 

http://www.nyc.gov/html/dot/html/about/datafeeds.shtml

The Department of Transportation provides detailed info on selected projects, including some web mapping viewers.  There may also be downloadable datasets under the second link (see "NYC DOT 10 Year Street Reconstruction Capital Plan").  Though as of writing this page (Fall 2018) the download on DOT's site yields a 2015 dataset.





