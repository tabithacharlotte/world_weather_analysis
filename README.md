# World Weather Analysis

## Overview of Project

At the most fundamental level, I needed to answer the question: How might we provide real-time suggestions for a travel client's ideal hotels? 

My first task was to define "ideal." So, I narrowed my definition to hotels that were (1) within a given range of latitude and longitude and that (2) provided the right kind of weather for a client based on temperature preferences.

I then wrote code that used weather data to recommend and visualize ideal hotels based on clients' weather preferences.

To test the project, I used input statements to filter data for weather preferences, which then identified potential travel destinations and nearby hotels. 
From the list of potential travel destinations, I chose four cities to create a travel itinerary. 
Finally, using the Google Maps Directions API, I created a travel route between the four cities as well as a marker layer map.

## Resources

- Data Source: OpenWeatherMap, Google Maps
- Software: JupyterNotebook , Pandas Library

## File Organization
- Weather_Database Folder
  - `Weather_Database.ipynb` file which contains code and process for how I retrieved information from an API call to OpenWeatherMap.
  - `WeatherPy_Database.csv` file which contains the weather data I collected in a csv.
- Vacation_Search Folder
  - `Vacation_Search.ipynb` file that contains code for creating a customer travel destination .
  - `WeatherPy_vacation.csv` file output that contains hotel names for hotels that fall within a customer's ideal temperature zones.
  - `WeatherPy_vacation_map.png` image of a travel destination map for ideal temperature zones.
- Vacation_Itinerary Folder
  - `Vacation_Itinerary.ipynb` file which has code that used Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations.
  - `The WeatherPy_travel_map.png` image of a travel itinerary that shows the route between four cities.
  - `The WeatherPy_travel_map_markers.png` image showing a marker layer map with a pop-up marker for each city on the itinerary.