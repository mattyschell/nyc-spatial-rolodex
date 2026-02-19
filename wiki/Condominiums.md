The Department of Finance publishes condominiums on the [Property Information Portal](https://propertyinformationportal.nyc.gov/).  The Condo data contains one or more records for each condominium complex in New York City. The unique key for this table is Condo_Key concatenated with Condo_Base_BBL (boro, block,lot). 

In those instances where a condominium exists on multiple base lots, multiple records will exist in this table. Each record can only have a single billing lot. 

To support the Property Information Portal the Department of Finance publishes a condo service on the [NYCMaps](https://nyc.maps.arcgis.com/home/index.html) ArcGIS Online organization.  The Department of Finance also publishes this data in some form on the NYC Open Data Portal.

See [Tax-Map](./Tax-Map.md) for more background.


## NYCMaps ArcGIS Online

This is what you want. 

Condo (non spatial) service updated monthly (stable)

* https://services6.arcgis.com/yG5s3afENB5iO9fj/arcgis/rest/services/Digital_Tax_Map_VIEW/FeatureServer/7

Condo (non spatial) service updated daily

* https://services6.arcgis.com/yG5s3afENB5iO9fj/arcgis/rest/services/DTM_ETL_DAILY_view/FeatureServer/3


## NYC Open Data

Department of Finance Digital Tax Map collection
* https://data.cityofnewyork.us/browse?Data-Collection_Data-Collection=Department+of+Finance+Digital+Tax+Map


