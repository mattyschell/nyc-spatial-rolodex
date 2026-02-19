The Department of City Planning releases borough boundaries via the Open Data Portal. 


### Open Data Portal

Water Included:

https://data.cityofnewyork.us/City-Government/Borough-Boundaries-Water-Areas-Included-/tv64-9x69

Clipped to Shoreline

https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm

The description for this dataset says "water excluded" but doesn't in fact exclude interior water.  The Department of Information Technology and Telecommunications maintains non-published landmass and borough datasets that exclude interior water, see [NYC_Landmass](https://github.com/mattyschell/NYC_Landmass)

### Boundary Notes

For both datasets there are a couple of sections where the tiny island of Manhattan has greedily chomped off bits of what any secure large borough resident expects to be part of their borough.  See for example the low tide mark on the Brooklyn and Queens shorelines that defines the borough boundary, meaning that when dunking a basketball on the Pier 2 courts of Brooklyn Bridge Park you are dunking on Manhattan.  This factoid is less fun when you are a spatial data analyst who can't dunk and who generates sliver polygons when processing datasets that are clipped by borough boundaries.

There's also a chunk of Manhattan on the north side of the Spuyten Duyvill Creek named Marble Hill which earns its own Wikipedia page. https://en.wikipedia.org/wiki/Marble_Hill%2C_Manhattan

You also probably don't want to look too closely at Liberty Island.

Less controversial is the borough boundary line through Shooter's Island between the north shore of Staten Island and New Jersey.  This is correct but may draw unwanted attention on a cartographic product that shows only New York City.  Harried cartographers have been known to throw all of Shooter's Island to New York City since only birds live there.

There's historical and political inertia to keep these boundaries as they are, not least because when redistricting laws require contiguous shapes it can be advantageous to string some of these oddities together.  
 

### Other Sources

US Census Bureau Tiger Line shapefiles (layer type Counties and Equivalents)

https://www.census.gov/cgi-bin/geo/shapefiles/index.php

US Census Bureau Cartographic Boundary Files.  Generalized for 3 target map scales.

https://www.census.gov/geo/maps-data/data/cbf/cbf_counties.html





