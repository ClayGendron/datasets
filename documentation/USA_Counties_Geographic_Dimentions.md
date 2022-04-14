`USA_Counties_Geographic_Dimentions.geojson`

Updated as of April 4, 2018

https://www2.census.gov/geo/tiger/GENZ2017/shp/

## Notes

This is a geojson file that contains the coordinates of each county in the USA. The coordinates can be used to create a visualizaiton that projects the counties identical to a map. This data is comes the from the US Census as a .shp file which was then convereted to a .geojson file.

## Attributes

|Name|Type|Description|
|--|--|--|
|year|Date (YYYY)|election year|
|state|Text|state name|
|state_po|Text|U.S. postal code state abbreviation|
|county_name|Text|county name|
|county_fips|Text|county FIPS code|
|office|Text|President|
|candidate|Text|name of the candidate|
|party|Text|party of the candidate; takes form of DEMOCRAT, REPUBLICAN, GREEN, |LIBERTARIAN, or OTHER|
|candidatevotes|Number|votes received by this candidate for this particular party|
|totalvotes|Number|total number of votes cast in this county-year|
|version|Date (YYYYMMDD)|mode of ballots cast; default is TOTAL, with different |modes specified for 2020|
|mode|Text|date when dataset was finalized|