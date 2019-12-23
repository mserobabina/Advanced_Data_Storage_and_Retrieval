# Advanced_Data_Storage_and_Retrieval
## Background 
The Jupyter Notebook contains the climate analysis for precipitation and temperature in Honolulu, HI from 08-23-2016 to 08-23-2017 (last twelve months of data). It also looks at specific trip dates from 02-28-2017 to 03-05-2017 to model the climate temperature normals and precipitation based on historical weather data.

Also included an Flask API Application to query:
- Precipitations from last year
- Weather stations
- Temperature Observations (tobs) for the previous year
- Minimum temperature, the average temperature, and the max temperature for a given start and/or start-end range inclusive.
## Dataset Information
- Dataset date range from 01-01-2010 to 08-23-2017
- SQLite Database Schema:
![Image](https://github.com/mserobabina/Advanced_Data_Storage_and_Retrieval/blob/master/schema.PNG)
## Observable Trends
- Honolulu, Hawaii had up to 7 inches of rain in last twelve months. Months with more than 3 inches of rain include: September, October, February, April, and July
- The most active station indicates the lowest temperature (54.0°F), highest temperature (85.0°F), and average (71.7°F) of the last twelve months
- The aggregate weather data helps us find the daily normals for the trip dates (07-01-2017 to 07-14-2017). The visualization labeled 'Aggregate Daily Normals for Trip Dates' shows the temperature extremes for the trip (low 60°F and high 88°F) while the average predicted temperatures stay in the mid 70's
## Exploratory Climate Analysis (1 year)

![Image](https://github.com/mserobabina/Advanced_Data_Storage_and_Retrieval/blob/master/DataStorage/Images/Precipitation_Analysis.png)

![Image](https://github.com/mserobabina/Advanced_Data_Storage_and_Retrieval/blob/master/DataStorage/Images/Observation_Histogram.png)
## Trip Climate Analysis
![Image](https://github.com/mserobabina/Advanced_Data_Storage_and_Retrieval/blob/master/DataStorage/Images/DailyNormals.png)
