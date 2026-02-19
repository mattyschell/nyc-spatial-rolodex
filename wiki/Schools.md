# NYC Open Data - Filtered Points of Interest

https://data.cityofnewyork.us/City-Government/Points-Of-Interest/rxuy-2muj

Filter on the columns FACILITY_T for "2 = Education Facility" and FACI_DOM for your selection of different types of schools.

See https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_PointsOfInterest.md for more info on this dataset.  Points Of Interest are actively maintained by the Citywide Street Centerline maintenance team at the New York City Department of Information Technology and Telecommunications.  However the schools points may not be totally 100% accurate and current since the maintainers of this dataset rely on publicly available info sources and have no insider info on the machinations of the New York City Department of Education.  

# NYC Open Data - 2019 - 2020 School Point Locations

https://data.cityofnewyork.us/Education/2019-2020-School-Point-Locations/a3nt-yts4

NYC Open data published this on September 4, 2019 as a response to requests about the out of date "Public School Points" dataset (see next section).  This 2019-2020 dataset depicts schools, so for many spatial locations expect to find multiple points with different school names at that location. You may not see these stacked points if you are drawing them in GIS software. 

# NYC Open Data - Public School Points

https://data.cityofnewyork.us/Education/School-Point-Locations/jfju-ynrr

Don't use this.  The date on the downloaded file implies that it was created for the 2011-2012 school year and does in fact appear to be out of date.  Like many datasets on NYC Open Data the "update frequency" and "updated" dates do not bring facts to the situation.

# Department of City Planning - Facilities Database

https://www1.nyc.gov/site/planning/data-maps/open-data/dwn-selfac.page

See the limitations section and documentation on extracting different types of educational facilities.

http://docs.capitalplanning.nyc/facdb/

In a brief and likely inaccurate summary, it kinda looks like the heroes at the Department of City Planning are scraping the NYC Department of Education "Blue Book," aka the "Enrollment-Capacity-Utilization Report" and feeding those school names into the New York City geocoder Geoclient as a "Place" lookup.  

http://www.nycsca.org/Community/Capital-Plan-Reports-Data#Enrollment-Capacity-Utilization-69

# Department of Education - Polygons

The Department of Education maintains an inventory of school tax lot properties (polygons).  The Department of Education does not publish this dataset.  