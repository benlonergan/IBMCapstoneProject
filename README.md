# IBM Capstone Project #

**Introduction/Business Problem**
Problem: Deciding where to build a new police station in London.

My project will use the python skills which I have learnt so far to help decide where to build a new police station in London. I have chosen to address this problem because I have a genuine interest in what the data may reveal. Areas with a high crime rates may benefit from police station of close proximity to improve response time to crimes. In addition to crime data, the report will also use demographic data of each London Borough and statistical analysis to help drive decision making. This analysis may be of use to the govt/police to assist them in a decision to construct a new police station based on crime hotspots.


**Data**
The data used will be used is:
Crime Data:
•	The crime data is sourced from the London Datastore (https://data.london.gov.uk/dataset/london-borough-profiles)
•	It is a CSV file which contains a range of information for each borough in London. 
•	The London Datastore describe says the data “helps paint a general picture of an area by presenting a range of headline indicator data in spreadsheet form to help show statistics covering demographic, economic, social and environmental datasets for each borough, alongside relevant comparator areas.”
•	The CSV file will be downloaded and then the crime data for each borough will be extracted. 
Location Data:
•	The location data is sourced from CARTO (https://joshuaboyd1.carto.com/tables/london_boroughs_proper/public)
•	It is a GEOJson file which contains the polygon coordinates for each London Borough. 
•	This will be used to help develop a choropleth map for crime rates across each London Borough. 
Venue Data:
•	The venue data about police stations is from Foursqaure API call. 
•	Multiple data calls will be used from locations in each London borough to produce a map of all the current police station locations across London. 
•	This will be superimposed as markers with the Folium package. 
•	Geopandas can then be used to determine current number of police stations in each London borough. 

