# python-api-challenge

# WeatherPy:

Creating a python script to visualize the weather of over 500 cities of varying distances from the equator.

 1- OpenWeatherMap was used to retrieve data from the cities list that were generated. A series of scatter plots was then created to showcase the following relationships:

	▪	Latitude vs. Temperature

      ![With title] (output_data/Fig1.png "Latitude vs Temperature")
      ![](output_data/Fig1.png)
      ![alt text](https://github.com/[M0412]/[python-api-challenge]/blob/WeatherPy/output_data/Fig1.png?raw=true)
      (https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)

      ![No title](https://github.githubassets.com/images/modules/logos_page/GitHub-Fig1.png)
	▪	Latitude  vs. Humidity
	▪	Latitude vs. Cloudiness
	▪	Latitude vs. Wind Speed

2- The linear regression for each relationship was then computed. Plots were separated into Northern Hemisphere and Southern Hemisphere and a series of scatter plots was created to showcase the relationships shown below. Linear regression line, the model’s formula, and the r values also were all computed for each plot.

	▪	Northern Hemisphere: Latitude vs. Temperature
	▪	Southern Hemisphere: Latitude vs. Temperature
	▪	Northern Hemisphere: Latitude vs. Humidity
	▪	Southern Hemisphere: Latitude vs. Humidity
	▪	Northern Hemisphere: Latitude vs. Cloudiness
	▪	Southern Hemisphere: Latitude vs. Cloudiness
	▪	Northern Hemisphere: Latitude vs. Wind Speed
	▪	Southern Hemisphere: Latitude vs. Wind Speed


# VacationPy:

Jupyter notebooks, the geoViews Python library, and the Geoapify API were used to plan for future vacations, and a python script was used to do the following:

	▪	Create a map that displays a point for every city that was generated in part 1, the size of the point is the humidity in each city.
        ▪	Narrow down the data frame to the ideal weather condition.
	▪	Create a data frame to store the city, coordinates, and humidity.
	▪	Use the Geoapify API to find the first hotel located within 10,000 meters of my coordinates.
	▪	Add the hotel name and the country as additional information in the hover message for each city on the map. 


