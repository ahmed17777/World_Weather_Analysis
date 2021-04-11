# World_Weather_Analysis
Syed Ahmed 
April 04, 2021

## Overview 

In this project, I will be using Google APIs to pull weather data for different vacation locations and identifying potential travel destinations and nearby hotels based on weather preferences for Jack. A four city itinerary will be created and mapped using Google Maps Directions API to create a travel route between the four cities. 

## Weather Data 
Weather data is retrieved using a set of 2,000 random latitidues and longitudes using Pandas and OpenWeatherMap API. The following information is retrieved and added into a DataFrame for analysis: 

![data-6-1-current-weather-description](https://user-images.githubusercontent.com/45697471/114321693-0dd4b280-9aea-11eb-9dc8-b5f5de7ea614.png)

## Vacation Map 
The following is a vacation map made using Pandas and OpenWeatherMap API. It returns potential vacation cities that have a temperature range of 75 to 85F. 

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/45697471/114321513-22647b00-9ae9-11eb-9319-542d56a2b4ac.png)

## Vacation Itinerary 
Based on Jack's preferences, a vacation itinerary map is made that includes a road trip between four cities: Acapulco, Tecoanapa, Puerto Escondido, and Pochutla in Mexico. The itinerary map is made using Google's Directions API. 

![WeatherPy_travel_map](https://user-images.githubusercontent.com/45697471/114321598-a585d100-9ae9-11eb-94eb-0b6c4748d875.png)
