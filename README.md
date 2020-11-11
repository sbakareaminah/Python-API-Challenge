# Python API Homework - What's the Weather Like?

## Part I - WeatherPy

 The Python script analyze and visualize the weather of 500+ cities across the world of varying distance from the equator. It was accomplished, by utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api)

 Series of scatter plots were created to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Linear regression of Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude), relationship as below:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

This notebook has the following:

* Randomly selected at least 500 unique (non-repeat) cities based on latitude and longitude.
* weather check on each of the cities using a series of successive API calls.
*Print log of each city as it's being processed with the city number and city name.
*CSV of all retrieved data and a PNG image for each scatter plot.

### Part II - VacationPy





z
* The heat map displays the humidity for cities in weatherpy  

  ![heatmap](Images/heatmap.png)

* The DataFrame analyzed ideal weather condition. For example:

  * A max temperature lower than 80 degrees but higher than 70.

  * Wind speed less than 10 mph.

  * Zero cloudiness.

  * Rows without the three requirement were dropped.

  

* Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

* The hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.


