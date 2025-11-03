This readme file was generated on [2025-11-02] by [MACKENZIE DOPF]

GENERAL INFORMATION

Title of Dataset: TOD Indicator Results 
Author/Principal Investigator Information
Name: Mackenzie Dopf
ORCID: N/A
Institution: University of Calgary
Address: 2500 University Drive NW Calgary Alberta T2N 1N4 CANADA
Email: Mackenzie.dopf@ucalgary.ca


Date of data collection: 2025-09-20 to 2025-10-20
Geographic location of data collection: Calgary Alberta Canada
All data was gathered from free and open-source locations 


SHARING/ACCESS INFORMATION

Licenses/restrictions placed on the data: This data is licenced under the Creative Commons Attribute 4.0 International. https://creativecommons.org/licenses/by/4.0/

Links to publications that cite or use the data: N/A
Links to other publicly accessible locations of the data: N/A
Links/relationships to ancillary data sets: N/A
Was data derived from another source?
	If yes, list source(s): 
[producer] Calgary Open Data [Distributer] City of Calgary (2025), Land Use Districts. Retrieved from https://data.calgary.ca/Base-Maps/Land-Use-Districts/mw9j-jik5 
[producer] Calgary Open Data [Distributer] City of Calgary (2025), Schools. Retrieved from https://data.calgary.ca/Services-and-Amenities/Schools/fd9t-tdn2/about_data 
[producer] Calgary Open Data [Distributer] City of Calgary (2025), Transit LRT Stations Map. Retrieved from https://data.calgary.ca/Transportation-Transit/Transit-LRT-Stations-Map/c6ee-wk9g 
[producer] Calgary Open Data [Distributer] City of Calgary (2025), Calgary Business Licences Map. Retrieved from https://data.calgary.ca/Business-and-Economic-Activity/Calgary-Business-Licences-Map/5qyu-igab 
[producer] Calgary Open Data [Distributer] City of Calgary (2025), Parks Sites. Retrieved from https://data.calgary.ca/Recreation-and-Culture/Parks-Sites/i9fu-gjqj 
[producer] Calgary Open Data [Distributer] City of Calgary (2025), Community Services. Retrieved from --------!!!!

DATA & FILE OVERVIEW

File List:
TOD_Indicator_Totaled_Results
TOD_Indicator_Schools_Results
TOD_Indicator_Cmmunity_Services_Results
TOD_Indicator_Stores_Results
TOD_Indicator_Parks_Results
TOD_Indicator_Zoning_Results

METHODOLOGICAL INFORMATION

Description of methods used for collection/generation of data: 
I have 5 categories, and their Shapefile data was downloaded from the Calgary Open Data Portal and opened in ArcGIS. My categories are schools, stores, community services, parks, and zoning.

Methods for processing the data: 
First, in ArcGIS, I created a 600m buffer radius around each of the LRT stations. 

I then queried three of my five categories to break the tables into manageable and meaningful categories. Zoning was reduced Commercial [C-COR1, C-COR2] Mixed Use [MU-1, MU-2] and Residencial [M-H1, M-H2, M-H3, M-X1, M-X2]. Schools became elementary, junior high, high school, post secondary. Community Services were divided into Law and Health [court, PHS clinic, hospital, social deviance center], and Entertainment and Education [major attraction center, community center, library, visitor information]. I then summarized either the category or sub category separately of the data to count points or area within a 600m Euclidian distance from each LRT Station.

Once my data is categorized around my geographies, I bring the tables into excel with each category analyzed individually in its own sheet. 
Point Data Analysis: 
Points of each category or sub category are summed. I find their average across all stations. I find the ratio of their density within all of the 600m buffers compared to the density of all items in Calgary. 

Area Data Analysis: 
All areas were summed within their categories. I found the average coverage across all the stations.

Instrument- or software-specific information needed to interpret the data: 
No Software is needed to open this data. 

DATA-SPECIFIC INFORMATION FOR: [FILENAME] 

TOD_Indicator_Totaled_Results
Number of variables: 1
Number of cases/rows: 47
Variable List: Rank, all 5 indicators ranks cumulated together, no units associated. 
Missing data codes: N/A
Specialized formats or other abbreviations used: N/A

TOD_Indicator_Schools_Results
Number of variables: 6
Number of cases/rows: 47
Variable List: elementary, junior high, high school, postsecondary and a count of those within a TOD area. I also have total where each school is combined for each station. and I have rank, with the stations ordered lowest to highest. 
Missing data codes: *list code/symbol and definition*
Specialized formats or other abbreviations used: 

TOD_Indicator_Cmmunity_Services_Results
Number of variables: 10
Number of cases/rows: 47
Variable List: Within the category of 'entertainment and recreation' I have four variables: major attraction center, recreation center, library and visitor information. The second category 'law and health' has court, PHS clinic, social deviance center and hospital. Total has all the community services at each station. the rank is those totals organized from smallest to largest. There are no units associated with this data. 
Missing data codes: N/A
Specialized formats or other abbreviations used: N/A

TOD_Indicator_Stores_Results
Number of variables: 2
Number of cases/rows: 47
Variable List: Total stores in each TOD and they are ranked from smallest to highest. There are no units associated with this data.
Missing data codes: N/A
Specialized formats or other abbreviations used: N/A

TOD_Indicator_Parks_Results
Number of variables: 4
Number of cases/rows: 47
Variable List: Park area: the total area designated as park within the TOD zone measured in hectares. Percent Area: that total area converted to a ratio of the total 600 m buffer area with no units. total percent area: the percent area ranked from smallest to highest and has no units. 
Missing data codes: N/A
Specialized formats or other abbreviations used: N/A

TOD_Indicator_Zoning_Results
Number of variables: 20
Number of cases/rows:47 
Variable List: The zoning are split into 3 catagories each having their own sub categories. Commercial: C-COR1, C-COR2. Mixed Use: MU-1, MU-2. Residencial: M-H1, M-H2, M-H3, M-X1, M-X2 and all are measured in hectares. Each hector area has a relative percent coverage area of the 600m TOD buffer. *list variable name(s), description(s), unit(s) and value labels as appropriate for each*
Missing data codes: N/A
Specialized formats or other abbreviations used: N/A


