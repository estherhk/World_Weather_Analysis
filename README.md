# World_Weather_Analysis

## Project Overview
Travel company, PlanMyTrip, requested an analysis pertaining to weather data to provide hotel/city suggestions for customers wanting to plan a trip.  Questions include minimum/maximum temperature, and if they want rainfall and/or snowfall.   

## Resources
Data Source:cities.csv
Software: Python 3.7, Jupyter Notebook
URL: OpenWeather, Google Maps

## Part 1 Summary

With a set of 2,000 random latitudes and longitudes, a DataFrame was created that includes the following information from the API call:
1) Latitude and longitude
2) Maximum humidity
3) Percent humidity
4) Percent cloudiness
5) Wind speed
6) Current description
7) Rain inches (last 3 hrs)
8) Snow inches (last 3 hrs)

### Image of DataFrame Summary
<img width=“500” alt=“” src="https://github.com/estherhk/World_Weather_Analysis/blob/master/weather_data/DataFrame_summary.png">

This explains 500+ cities and their current description of weather.  Curently, there are <b>53 cities</b> that have recorded <b>rainfall</b> and <b>33 cities</b> that have recorded <b>snowfall</b> in the last 3 hours.

## Part 2 Summary

To help customers narrow their travel searches based on temperature and precipitation, questions were asked:
1) What is the minimum temperature you would like for your trip? 
2) What is the maximum temperature you would like for your trip? 
3) Do you want it to be raining? (yes/no) 
4) Do you want it to be snowing? (yes/no) 

A DataFrame will generate with information that matches the customers answers, and then a marker layer map on Google Maps will appear with the information for suggested hotel, city, county, and current weather.

### Image of Cities that Match the Customers Needs

<img width=“500” alt=“” src="https://github.com/estherhk/World_Weather_Analysis/blob/master/weather_image/WeatherPy_vacation_map.png">

## Part 3 Summary

In the directions layer map, there are four cities(San Clemente, CA, Ballstad, CA, Portland, OR, and Port Hardy, Canada) that are marked for a possible west coast trip in the United States and Canada. For travel mode, driving is the preferred option.  Pop-up markers were created in the marker layer that contain the following:
1) Hotel Name
2) City
3) Country
4) Current weather description with maximum temperature

### Image of Vacation Map
<img width=“500” alt=“” src="https://github.com/estherhk/World_Weather_Analysis/blob/master/weather_image/WeatherPy_travel_map.png">

### Image of Pop-Up Markers
<img width=“500” alt=“” src="https://github.com/estherhk/World_Weather_Analysis/blob/master/weather_image/WeatherPy_travel_map_markers.png">

## Challenge Overview

With a set of 2,000 randomly generate latitudes and longitudes to equal 500+ cities, DataFrames were created to create maps that would answer the following questions:

1) Include weather description in pop-up markers for customers so that they know what the weather is as they are traveling
2) A notation in the search criteria to indicated if it is raining or snowing for customers who are making travel decisions in real-timer 3) A map that shows the directions for customers' travel itinerary  
