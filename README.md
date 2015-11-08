# Mapping LA's buildings at risk during an earthquake with open data (Draft 11.8.2015)

This is an exploration of how far online sources and open data can be used to locate, and identify wood-frame residential buildings at risk during an earthquake in the City of Los Angeles. This effort will document the sources, people, data, methods, analysis and limitations of open data.

##Background

###Council Motion 13-0964
In July 31, 2013, the Los Angeles City Council filed a motion [13-0964](http://clkrep.lacity.org/onlinedocs/2013/13-0964_mot_07-31-13.pdf), instructing the Department of Building and Safety (LADBS) to 
> provide to the City Council a comprehensive proposal for how the department can identify and account for wood-frame soft-story residential buildings (with two or more stories, and 5 or more units) built prior to 1978 that exist in the City. ([13-0964](http://clkrep.lacity.org/onlinedocs/2013/13-0964_mot_07-31-13.pdf))

These buildings, known as soft-story buildings according to LADBS are by definition
> Typical wood-frame soft-story buildings are two or more stories buildings with large openings in exterior wall(s) at the ground level mainly because of parking garages or other similar open floor space that causes a soft and/or weak story. ([LADBS report in response to council motion 13-0964](http://clkrep.lacity.org/onlinedocs/2013/13-0964_rpt_dbs_11-22-13.pdf))

Such structures are at risk during an earthquake because
>their ground floor generally have perimeter walls that lack adequate strength. Hence, during an earthquake, lateral forces become concentrated within that story, instead of being distributed efficiently over the height of the structure. Consequently, the building is liable to "pancake" and collapse. ([13-0964](http://clkrep.lacity.org/onlinedocs/2013/13-0964_mot_07-31-13.pdf))

The motion, was approved by the council in June of 2014 [13-0964](https://cityclerk.lacity.org/lacityclerkconnect/index.cfm?fa=ccfi.viewrecord&cfnumber=13-0964), authorizing LADBS to create a list. The report by LADBS established a methodology by:
* Step 1: Establish a Base List by Using Housing Department's Data
* Step 2: Narrow Down the Base List by Utilizing Mapping Programs and LADBS Records
* Step 3: Finalize the List by Performing Site Inspections

Since then it was announced that LADBS will release the completed list by Febuary 2016 in conjunction with Ordinance 183893, mandating building owners on this list to retrofit their buildings.


###[LA City Ordinance 183893](http://ladbs.org/LADBSWeb/LADBS_Forms/PlanCheck/Ordinance_183893.pdf): Mandatory Earthquake Hazard Reduction in Existing Wood-Frame Buildings with Soft, Weak or Open Front Walls
In October 14, 2015, the Los Angeles City Council approved an ordinance that mandates owner's of thousands of wooden apartment buildings at risk of collapse to retrofit their building. According to the [LA Times](http://www.latimes.com/local/lanow/la-me-ln-la-buildings-quake-retrofit-20151105-story.html), the ordinance will give property owners:
* Seven years to strengthen "soft-story" wooden apartments.
* 25 years for concrete buildings.

###LADBS Report Findings
The report response by LADBS provided the following information on the approximate number of buildings affected.

| Group | Type of Apartment Building Groups                   | Approximate % of Buildings | Number of Buildings |
|-------|-----------------------------------------------------|----------------------------|---------------------|
| 1     | Non soft-story buildings                            | 40%                        | 11,690              |
| 2     | Soft-story buildings                                | 20%                        | 5,846               |
| 3     | Buildings that cannot be identified in Group 1 or 2 | 40%                        | 11,690              |
| 3     | Buildings that cannot be identified in Group 1 or 2 | 40%                        | 11,690              |


##Open Data Approach
While awaiting the LADBS list to completed and released, I wondered if it was possible to identify these buildings with data that is already available. Recent map projects, like [builtla.cityhub.la](cityhubla.github.io/LA_Building_Age), utilized property data from the LA County Assessor, identifying the age of buildings throughout the county. The [LA County Local Tax roll](http://assessor.lacounty.gov/local-roll/), contains many data fields like:
* The year a building was built on a property
* The number of buildings on a property
* The general and specific uses of a building on a property
* Number of units in the building or buildings on a property

The information on this dataset alone, offers an amazing look into the issues of land use development in LA County and its 88 cities.

The assessor's parcel data will be used in combination with other datasets to hopefully identify these soft-story buildings and create a webmap-type narrative of the steps taken.

###Known Datasets
* [LA County Assessor 2014 Parcel Geodatabase](http://egis3.lacounty.gov/dataportal/2015/03/10/assessor-parcel/)
* [LA Countywide Building Outlines Shapefile](http://egis3.lacounty.gov/dataportal/2011/04/28/countywide-building-outlines/)
* [LA Times: Concrete Buildings List from UC Berkeley CSV](http://graphics.latimes.com/static/csv/la_concrete_buildings.csv)

###Steps

###Descrepancies

###Conclusion
