# python-api-challenge

# WeatherPy:

Creating a python script to visualize the weather of over 500 cities of varying distances from the equator.

 1- OpenWeatherMap was used to retrieve data from the cities list that were generated. A series of scatter plots was then created to showcase the following relationships:

	▪	Latitude vs. Temperature
  ![Fig1](https://github.com/M0412/python-api-challenge/assets/133132845/64c0107e-24c6-4c47-8d3e-a4833c4a386b)

      
	▪	Latitude  vs. Humidity
  ![Fig2](https://github.com/M0412/python-api-challenge/assets/133132845/60ef396a-c2f3-40c9-9921-e68590085a4b)

      
	▪	Latitude vs. Cloudiness
  ![Fig3](https://github.com/M0412/python-api-challenge/assets/133132845/f5d60628-0590-41a2-ada8-f5795a282371)
    
      
	▪	Latitude vs. Wind Speed
  ![Fig4](https://github.com/M0412/python-api-challenge/assets/133132845/545cb577-1090-4f5b-99ae-0857bd0c7af6)
 
      
2- The linear regression for each relationship was then computed. Plots were separated into Northern Hemisphere and Southern Hemisphere and a series of scatter plots was created to showcase the relationships shown below. Linear regression line, the model’s formula, and the r values also were all computed for each plot.

	▪	Northern Hemisphere: Latitude vs. Temperature
  ![Fig5](https://github.com/M0412/python-api-challenge/assets/133132845/d7ec9864-68cc-4080-9138-5cf5d4747598)

	▪	Southern Hemisphere: Latitude vs. Temperature
  ![Fig6](https://github.com/M0412/python-api-challenge/assets/133132845/e21bc661-5088-4e5e-ad37-0ca684293cb6)

	▪	Northern Hemisphere: Latitude vs. Humidity
  ![Fig7](https://github.com/M0412/python-api-challenge/assets/133132845/b240aa72-1904-4341-8c76-2c8d1c40826d)

	▪	Southern Hemisphere: Latitude vs. Humidity
  ![Fig8](https://github.com/M0412/python-api-challenge/assets/133132845/e0d87b7d-d179-4749-ae13-17737efcba0a)

	▪	Northern Hemisphere: Latitude vs. Cloudiness
  ![Fig9](https://github.com/M0412/python-api-challenge/assets/133132845/68124047-80d1-4141-833b-2924b415bab5)
 
	▪	Southern Hemisphere: Latitude vs. Cloudiness
  ![Fig10](https://github.com/M0412/python-api-challenge/assets/133132845/c493b275-2050-49ec-89c8-f6ee1e555047)
 
	▪	Northern Hemisphere: Latitude vs. Wind Speed
  ![Fig11](https://github.com/M0412/python-api-challenge/assets/133132845/8385464f-24a8-413e-8ee8-b626c66d6fca)

	▪	Southern Hemisphere: Latitude vs. Wind Speed
  ![Fig12](https://github.com/M0412/python-api-challenge/assets/133132845/ad41d0ee-b60f-4bac-a774-0b64e1ae3378)


# VacationPy:

Jupyter notebooks, the geoViews Python library, and the Geoapify API were used to plan for future vacations, and a python script was used to do the following:

	▪	Create a map that displays a point for every city that was generated in part 1, the size of the point is the humidity in each city.
        ▪	Narrow down the data frame to the ideal weather condition.
	▪	Create a data frame to store the city, coordinates, and humidity.
	▪	Use the Geoapify API to find the first hotel located within 10,000 meters of my coordinates.
	▪	Add the hotel name and the country as additional information in the hover message for each city on the map.
     
 
![map2](https://github.com/M0412/python-api-challenge/assets/133132845/4c66d678-0ce0-446e-b9a0-7a65d7856d07)



