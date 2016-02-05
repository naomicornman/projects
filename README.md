#About the dataset
The National Oceanic and Atmosphere Adminstration (NOAA) shares Storm Data, which documents the occurrence of storms and other significant weather phenomena having sufficient intensity to cause loss of life, injuries, significant property damage, and/or disruption to commerce. I was searching for a dataset that is envrionment related. With climate change and changing weather patterns, storms one of the most visible threat. 

##Basic facts about the dataset
- The source of the data: [National Climatic Data Center, National Oceanic and Atmosphere Adminstration](http://www.ncdc.noaa.gov/)
- The data's landing page: [Storm Data](http://www.ncdc.noaa.gov/stormevents/ftp.jsp)
- Direct link to the data: [For year 2015](ftp://ftp.ncdc.noaa.gov/pub/data/swdi/stormevents/csvfiles/)
- The data format: CSV
- Number of rows: 54,400

##Description of data fields
YEARMONTH
Year and month of storm incident in this **integer** format: "201506"

EPISODE_ID
5 digit **integer** that represents an entire storm system and can contain many different types of events.

EVENT_ID
6 digit **integer** that represents individual type of storm event, for example thunderstorm, wind, hail, tornado and flood.

LOCATION_INDEX
Contains **integer**, where all listings are between 1 and 6. 

RANGE
Range of storm in this **float** format: "0.57"

AZIMUTH
The azimuth is the angle between the north vector and the perpendicular projection of the star down onto the horizon. #string Format: "WSW," or "E."

LOCATION
County name in this **string** format: "ARTHUR"

LATITUDE
Contains **float** in this format: "33.97"

LONGITUDE
Contains **float** in this format: "-81.16"

LAT2
Contains **integer** in this format: "3358200"

LON2
Contains **integer** in this format: "819600"

##Anticipated data wrangling
- First, I need to figure out what "LOCATION_INDEX" signifies. 
- Second, I will have to decide how to sort, based on episode or event. 
- Third, I will have to decide how to plot the range of a storm. 
