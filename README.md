# World Weather Analysis

## Description

PlanMyTrip app allows customers to plan their vacation and find hotels based on their preferrences.<br>
After extracting current weather data and Google maps using API keys, maps were created based on customer inputs.

#### *Folder 1* - [Weather_Database](https://github.com/JediMasterSlagle/World_Weather_Analysis/tree/main/Weather_Database)

Includes:<br>
**Weather_Database.ipynb** - code used to generate coordinates, cities and pull a request using the Open Weather Map API key to extract current weather and description.<br>
**WeatherPy_Database.csv** - all data compiled and converted to a CSV file.


#### *Folder 2* - [Vacation_Search](https://github.com/JediMasterSlagle/World_Weather_Analysis/tree/main/Vacation_Search)

Includes:<br>
**Vacation_Search.ipynb** - code to take user input when selecting the preferred weather for vacation.  Based on their selection, they can pull up potential travel destinations.<br>
**WeatherPy_vacation.csv** - data complied and converted to a CSV file.<br>
**WeatherPy_vacation_map.png** - image of the map with markers showing; city, country, hotel name and current weather description.


#### *Folder 3* - [Vacation_Itinerary](https://github.com/JediMasterSlagle/World_Weather_Analysis/tree/main/Vacation_Itinerary)

**Vacation_Itinerary.ipynb** - code used to filter and select cities.  Using the Directions API, we can easily see and plan travel paths and duration for each city with an overall view of the trip as a whole, driving being the method of travel.<br>
**WeatherPy_travel_map.png** - map of the 4 cities with a planned out travel route.<br>
**WeatherPy_travel_map_markers.png** - map of 4 cities and the hotels available within each city.  Pop markers included to show; city, country, hotel name and current weather description.