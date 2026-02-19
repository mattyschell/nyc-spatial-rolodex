General refresher on United States Postal Service (USPS) ZIP codes, which aren't real geographies, and ZIP Code Tabulation Areas (ZCTAs, pronounced "zic-tuhs"), which are approximations of ZIP codes.

https://github.com/iandees/wtf-zipcodes

Since ZIP codes aren't even real geographies to begin with, they are super susceptible to the modifiable areal unit problem.

https://en.wikipedia.org/wiki/Modifiable_areal_unit_problem

The USPS site for pricing direct mailers may be useful for visualizing mail carrier routes and PO boxes relative to USPS ZIP codes: 

https://eddm.usps.com/eddm/customer/routeSearch.action

If you read all of the above and, thus familiarized, still want to use ZIP codes good luck with the data sources below.

### NYC Open Data

NYC Open data removed ZIP Codes from the open data portal in 2023.

Many members of the public pointed out what they considered to be inaccuracies in the ZIP Code boundaries. Without an authoritative source the GIS experts felt it best to remove the ZIP Codes. No ZIP Codes was preferable to making implied claims about the legacy ZIP Codes on NYC Open Data being authoritative in any way.

### NYC Street Centerline Database

The Office of Technology and Innovation, in partnership with the Department of City Planning, maintains a polygon ZIP Code feature class in the Citywide Street Centerline (CSCL) database.  The data is not published and has not been edited in many years.  

The polygons in this dataset overlap, with smaller ZIP codes fully contained within larger ZIP codes (ex 10151 contained by 10022).  Most mapping software orders shape rendering by the order of records in the data, usually a synthetic key.  So a naïve mapping of these ZIP codes will often cause 10151 to disappear "behind" 10022.

Some staff at the NYC Office of Technology and Innovation recall that these ZIP codes were hand crafted from US Census Bureau ZIP Code Tabulation Areas after the 2000 census.  NYC ZIP Codes may have been updated by hand as recently as around 2010 as new US Postal Service ZIP codes came online.  At some point the updates to the NYC file stopped and the same NYC ZIP Code boundaries have been kicking around city agencies as the official ZIP codes for years with little attention paid to details like you are for some reason reading on this page.

Internal legacy tools in the CSCL database continue to apply these ZIP Codes to street centerlines. The Department of City Planning periodically corrects centerline ZIP codes where commercial data does not match the ancient ZIP Code polygon boundaries in the database.  

### Other Sources

US Census Bureau Tiger Line Shape Files (ZCTAs)

https://www.census.gov/cgi-bin/geo/shapefiles/index.php

US Census Bureau ZCTA Cartographic Boundary Files ("cartographic" = "generalized").  

https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html

### Geocoding and Addresses

Given an address we can also derive ZIP Codes from New York City's geocoders.  See for example:

* GOAT (http://a030-goat.nyc.gov/goat/Default.aspx)
* Geosupport (https://www1.nyc.gov/site/planning/data-maps/open-data/dwn-gde-home.page)
* Geoclient (https://api.cityofnewyork.us/geoclient/v1/doc)

ZIP codes are also baked into [[Address-Points]]

All three of the links above should return the same ZIP code for an address.  Given the buffet of ZIP code boundaries available however, the ZIP code returned may or may not correspond to any of the other known ZIP code boundaries.

Seriously, are you still reading this?  Well then you may be the only other person interested in a case where an address can be in different ZIP codes depending on the source. 55 Water Street (https://en.wikipedia.org/wiki/55_Water_Street) is an interesting address both because of the massive but rarely commented-upon building at that address, and also because (and possibly related) it belongs to either ZIP code 10041 or 10004.










