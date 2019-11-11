# jmerkel_Module_06
##APIs
This file contains weather data for a randomized set of cities and a sample travel itinerary for a South-East Australian trip.

Using a randomized set of coordinates, the program calls the nearest_city function of the citipy module to apply a city name to each coordinate.

From there, each city is used to call the Open Weather Map API for up to date weather forecasts. Using the information gathered here, users can filter cities offered by providing a temperature range as well as a status of rain or snow in the last 3 hours.

Finally, the administrator (me) picked 4 cities to create a sample trip based on user input. Using gmaps direction API calls, a map and directions were generated. 

###code
.ipynb files are located in the base directory

###CSV files
csv files are located in the "weather_data" directory

###Screenshots
screenshots are located in the "weather_image" directory
