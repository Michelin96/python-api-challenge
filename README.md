# python-api-challenge

The WeatherPy code collects API data from a random selection of 500 or more cities around the globe. The data from those cities is plotted to determine if there is a correlation between the latitude and weather.

* In plotting latitude vs temperature, the temperatures increased as the cities neared zero latitude, that is the equator.

* The latitude vs humidity scatter plot has a concentration of cities with high humidity at latitudes between 50 and 80.

* Looking at latitude vs wind speed, there is a higher concentration of wind speeds up to 10 mph in cities between 30 and 70 degrees latitude.

* Temperatures in the Norhtern hemisphere show a moderate positive correlation to latitude while the Southern hemisphere shows a strong positive correlation. In both hemispheres, there is almost no latitude correlation to weather patterns in humidity, cloudiness, and wind speed. Based on this analysis, only temperature is effected by latitude.

In the VacationPy code, google maps is used to show the humidity at the random cities that were collected in WeatherPy. The weater data that was collected is used to locate several cities that meet an ideal vacation climate. This ideal climate is between 70-83F with <10% cloudiness, wind <10 mph, and humidity < 45%. For each ideal climate location, the nearest hotel is found and marked on a map.
