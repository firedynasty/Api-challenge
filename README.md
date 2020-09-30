# python-api-challenge

## WeatherPy Challenge

In this activity, the goal is to find differences of temperature, humidity, cloudiness, and wind speed between cities spaced apart from the equator latitudionally. 

From the results, it appears that there is strong correlation between temperature and where the city is located.  As a city is farther away from the equator, the city has colder temperatures. 

There is not much correlation between temperature, humidity, and cloudiness, comparing different cities latitudionally. 

The library `citipy` was used to generate the city names.  The library `random` was used to generate random numbers between -180 to 180 for the longitude, and -90 to 90 for the latitude.  The number of cities generated was over 500.  

The API call to Openweather API responded with data of the cities, and the data of latitude, max_temp, humditity, cloudiness, windspeed, country, and time were returned as lists.  The DataFrame by the name of `cities_info_df` was created from these lists. 

Pandas Plot was used to plot between latitude and the temperature, humudity, cloudiness, and the wind speed. 

Regression lines and R values were applied to the graphs.  

The graphs with correlation are shown below (between latitude and temperature):

It should be noted that there is stronger correlation between the cities in the Northern Hemisphere vs. the Souther Hemisphere (0.71 vs 0.46)

![Image of Northern_and_Southern](https://github.com/firedynasty/python-api-challenge/blob/master/Images/north_and_south_hemisphere.png)
