"LION is a single line representation of New York City streets containing address ranges and other information."

LION is an acronym for Linear Integrated Ordered Network but few among the living know this. Everyone refers to it as "lion," like the big kitty.  It was named to be similar to the US Census Bureau's [TIGER](https://en.wikipedia.org/wiki/Topologically_Integrated_Geographic_Encoding_and_Referencing)

### New York City Department of City Planning

The New York City Department of City Planning releases the LION file several times a year, with names in the format "nyclion_yy[a-z]" like "nyclion_19a" for the first release of 2019.

The downloadable format is ESRI geodatabase only and is around 40 MB zipped. See also the REST endpoint and GEOJSON service.  

https://www1.nyc.gov/site/planning/data-maps/open-data/dwn-lion.page

### New York City Open Data

This appears to be a copy of the file available on the Department of City Planning download page though it may be a release behind the definitive source.  The Open Data page also includes archived versions from prior years.

https://data.cityofnewyork.us/City-Government/LION/2v4z-66xt

### Usage Notes

Be advised that LION street segments are divided into smaller bits anywhere that other linear features (political boundaries, etc) in the source database cross the streets. Expert LION users may refer to these division points as "pseudo-nodes."

LION street segments may also be stacked up on top of each other.  This can happen when streets are in a double decker configuration in the real world (like on a bridge) or when streets have more than one name.  

So use caution if labeling streets using the LION dataset.  And know that the phrase "single line representation" in the LION docs has a specific but somewhat counterintuitive definition.