# SQLAlchemy-Homework
Using the Jupyter Notebook I have done a climate analysis from 08-23-2017 to 08-23-2017 for precipitation and temperature in Honolulu, HI. I have also added a search on specific trip dates from 07-01-2017 to 07-14-2017 to model the climate temperature normals and precipitation based on historical weather data. 

Also included an Flask API Application to query: 

* Precipitations from last year 
* Weather stations
* Temperature Observations (tobs) for the previous year
* Minimum temperature, the average temperature, and the max temperature for a given start and/or start-end range inlcusive.

# Dataset Information 

* Dataset date range from 01-01-2010 to 08-23-2017
* SQLite Database Schema: 
https://github.com/daryaroshan/SQLAlchemy-Homework/blob/master/Images/schema.png

# Trends 
* Honolulu, Hawaii had up to 7 inches of rain in last twelve months. 
* September, October, February, April, and July were months with more than 3 inches of rain.
* Considering the most active station, temperatures of the last twelve months were as follows:
   -lowest temperature (54.0°F)
   -highest temperature (85.0°F)
   -average (71.7°F)  
 * The aggregate weather data helps us find the daily normals for the trip dates (07-01-2017 to 07-14-2017). The visualization labeled 'Aggregate Daily Normals for Trip Dates' shows the temperature extremes for the trip (low 60°F and high 88°F) while the average predicted temperatures stay in the mid 70's.

# Climate Analysis
https://github.com/daryaroshan/SQLAlchemy-Homework/blob/master/Images/WeatherCondition.png
https://github.com/daryaroshan/SQLAlchemy-Homework/blob/master/Images/station-histogram.png

# Trip Climate Analysis 
https://github.com/daryaroshan/SQLAlchemy-Homework/blob/master/Images/TripAvgTemp.png
https://github.com/daryaroshan/SQLAlchemy-Homework/blob/master/Images/DailyNormals.png
