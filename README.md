# World_Weather_Analysis

## Overview
In this challenge, I was tasked with creating a DataFrame containing cities and weather data.  I had to pull data for the cities from the Open Weather Map API, and use it to look up hotels that are located in cities matching a customer's temperature constraints, and develop a vacation itinerary.

## Results
For this challenge, the results exist in the form of DataFrames and maps.  The maps visualize the DataFrame information. THe first map I created shows all the potential vacation destinations before a temperature constraint was applied. 

<img width="1002" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/99457275/163003590-a17fec51-ec1a-466b-85fb-5bd72c295612.png">

The second map shows the driving route for the four selected vacation cities.

<img width="882" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/99457275/163003887-19f4ed80-26af-43e9-ac34-27a75b5ab616.png">

The final map shows the vacation destinations with a marker layer that shows weather conditions in the city at the time the code is run.

<img width="885" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/99457275/163004009-aaba4d41-2749-4360-8c53-b7c0ec05e5e5.png">

I initially chose different cities for the vacation itinerary, but in order to better display the marker layer, I chose to space the cities out more.

## Summary

In summary, I was able to create a program that gives travelers the ability to refine a vacation itinerary based on temperature constraints.  One recommendation would be to figure out if the size of the marker layer boxes can be decreased to better allow for the map to be visible.
