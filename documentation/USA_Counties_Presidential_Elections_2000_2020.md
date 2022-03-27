`USA_Counties_Presidential_Elections_2000_2020.csv`

Updated as of Jun 8, 2021

https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/VOQCHQ

## Notes

This data set contains county-level returns for presidential elections from 2000 to 2020. The data source is official state election data records.

Note: County results in Alaska for 2004 are based on official Alaska data, but it is clear the district returns significantly overstate the number of votes cast.

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