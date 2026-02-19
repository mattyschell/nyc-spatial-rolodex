Sanitation Sections are the sub-geography in which Department of Sanitation garages manage their work. Sanitation Sections are commonly referred to as "DSNY Sections" and pronounced "Dee-Ess-En-Why Sections."

Sanitation Sections are built from one or more [Community-Districts](./Community-Districts.md).  Sanitation Sections nest within [Sanitation-Districts](./Sanitation-Districts.md) which in turn nest within [Sanitation-Zones](./Sanitation-Zones.md).

Sanitation Sections are named like "BKS062" which a sanitation geography pro will immediately interpret as Section 2 in [Sanitation-Districts](./Sanitation-Districts.md) 6 in the Brooklyn South [Sanitation-Zones](./Sanitation-Zones.md).  The Department of Sanitation defines and uses this section name.  Sanitation Sections also have codes like "3062" which is section 062 within Brooklyn Borough (borough code 3).  The Department of City Planning uses and defines Sanitation Section codes.  Yes, Sanitation Sections are awarded 2 different unique identifiers.

The Department of Sanitation does not use Sanitation Sections for snow operations and instead uses [Snow-Sectors](./Snow-Sectors.md).

### Department of Sanitation REST service

Working as of 2024 but may not be intended for public consumption. 

https://services.arcgis.com/uKN48PkxmWiqJM9q/ArcGIS/rest/services


### NYC Open Data

https://data.cityofnewyork.us/City-Government/DSNY-Sections-Map-/5hwa-9qfj

These boundaries occasionally change.  In the past the export options for this dataset split the records into two separate files. One file contains single outer ring polygons.  The second file contains records with multiple outer rings, commonly called "multipolygons."  This same weird split of the data also appears confusingly under the "download a specific layer's data" section.  

When contacted about this issue the NYC Open Data Team and/or the Department of Sanitation recommended using the Arcgis REST services directly from the Department of Sanitation.  The links to this service on NYC Open Data may not be working, and need to be changed from "http" to "https". See below.


### Geocoding and Sanitation Sections

Given an address we can also derive its Sanitation Section from New York City's geocoders.  They will return the code (ex 062) from the Department of City Planning. 

* GOAT (http://a030-goat.nyc.gov/goat/Default.aspx)
* Geosupport (https://www1.nyc.gov/site/planning/data-maps/open-data/dwn-gde-home.page)
* Geoclient (https://api.cityofnewyork.us/geoclient/v1/doc)


