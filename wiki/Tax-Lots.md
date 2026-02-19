The Department of Finance publishes tax lots on the [Property Information Portal](https://propertyinformationportal.nyc.gov/).  To support the Property Information Portal the Department of Finance publishes a tax lot service on the [NYCMaps](https://nyc.maps.arcgis.com/home/index.html) ArcGIS Online organization.  The Department of Finance also publishes these lots in some form on the NYC Open Data Portal.

See [[Tax-Map]] for more background.

Do not be fooled by the datasets named "Tax Lot **Face**" which describe lines around tax lots. Unless you are a tax map wizard you probably do not want to look at these lines.

Tax lots nest within [[Tax-Blocks]].


## NYCMaps ArcGIS Online

This is what you want. These services may have a defined maximum and minimum scale.  If you don't see any data you may need to override these scales.  For example in ArcGIS Pro navigate to "Layer Properties" and set the visibility range "In beyond" and "Out beyond" to none.

Tax lot service updated monthly (stable)

* https://services6.arcgis.com/yG5s3afENB5iO9fj/arcgis/rest/services/Digital_Tax_Map_VIEW/FeatureServer/5

Tax lot service updated daily

* https://services6.arcgis.com/yG5s3afENB5iO9fj/arcgis/rest/services/DTM_ETL_DAILY_view/FeatureServer/0

## NYC Open Data

Department of Finance Digital Tax Map collection
* https://data.cityofnewyork.us/browse?Data-Collection_Data-Collection=Department+of+Finance+Digital+Tax+Map
