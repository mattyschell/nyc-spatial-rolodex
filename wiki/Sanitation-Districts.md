Sanitation Districts are the middle-tier geography in which the Department of Sanitation manages work. Sanitation Districts are commonly referred to as "DSNY Districts" and pronounced "Dee-Ess-En-Why Districts."

Sanitation Districts nest within the top-level [[Sanitation-Zones]]. Sanitation Districts are built up from [[Sanitation-Sections]].  Sanitation Districts are similar to [[Community-Districts]], with most Sanitation Districts having a corresponding Community District with a matching code and similar boundaries.  However Sanitation Districts do not include territory that is not served by the Department of Sanitation, like airports and large parks.

Sanitation Districts are named like "BKS06" for district 6 within the Brooklyn South [[Sanitation-Zones]].  The Department of Sanitation defines and uses this name.  Sanitation Districts also have codes like "306" which is district 6 within Brooklyn Borough (borough code 3).  The Department of City Planning uses and defines Sanitation District codes.  Oh yes, this dataset uses 2 different unique identifiers.


### NYC Open Data

https://data.cityofnewyork.us/City-Government/DSNY-Districts/6j86-5s7z

These boundaries occasionally change, often in the fall in preparation for high-profile snow removal season. As of winter 2018 most of the export options for this dataset split the records into two separate files. One file contains single outer ring polygons.  The second file contains records with multiple outer rings, commonly called "multipolygons."  This same weird split of the data also appears confusingly under the "download a specific layer's data" section.  

When contacted about this issue the NYC Open Data Team and/or the Department of Sanitation recommended using the Arcgis REST services directly from the Department of Sanitation.  See below.

### Department of Sanitation REST service

Working as of May 2019 but may not be intended for public consumption.

https://services.arcgis.com/uKN48PkxmWiqJM9q/ArcGIS/rest/services

### Geocoding and Sanitation Districts

Given an address we can also derive its Sanitation District from New York City's geocoders.  They will return the code (ex 306) from the Department of City Planning. 

* GOAT (http://a030-goat.nyc.gov/goat/Default.aspx)
* Geosupport (https://www1.nyc.gov/site/planning/data-maps/open-data/dwn-gde-home.page)
* Geoclient (https://api.cityofnewyork.us/geoclient/v1/doc)
