The New York City Department of Information Technology and Telecommunications maintains points of interest as part of the NYC Street Centerline (CSCL) database.  For more background see https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_PointsOfInterest.md

# NYC Open Data 

https://data.cityofnewyork.us/City-Government/Points-Of-Interest/rxuy-2muj

The Department of Information Technology and Telecommunications extracts and uploads this dataset to the Open Data site weekly.

A typical filter of this data requires a combination of the FACILITY_T (facility type) and FACI_DOM (facility domain) columns.  For example, to extract all Police Precinct houses use a facility type of 11 (Public Safety) and facility domain of 1 (NYPD Precinct).

The metadata here (https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_PointsOfInterest.md) includes all valid combinations of facility type and facility domain.  Metadata on the NYC Open Data site is likely inaccurate or incomplete.


