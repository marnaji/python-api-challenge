# python-api-challenge
## Part1: WeatherPy
    I created the Python script to visualize weather of over 500 cities of varying distances from the equator. In this activity I created some scatter plots to showcase the relationship between weather variables and latitude, plus I computed Linear Regression for each relationship. 

    The scatter plotes series wich will showcase here are include four different relationships, such as Latitude vs. Temperature, Latitude vs. Humidity, Latitude vs. Cloudiness, and Latitude vs. Wind Speed. 

    Linear regression has been computed for each relationship. The plots has been separated into Northern Hemisphere and Southern Hemisphere. 

## Results WeatherPy
#### Latitude vs. Temperature
Correlation among Max Temperature and Latitude in Northern Hemishphere is negative and the higher the Latitude the lower Temperature. Correlation among Max Temperature and Latitude in Sothern Hemisphere shows a positive relation and with increase of the Temperature the Latitude goes up.
r_value:
    Northern : 0.6409014602340861
    Southern : 0.8318082534886896

![alt text](/images/NorthTemp.png)![alt text](/images/SouthTemp.png)
#### Latitude vs. Humidity
orthern Hemisphere Latitude has a low positive correlation with humidity the increase latitude cause the humidity goes slowly higher. Sothern Hemisphere Humidity has a negative relation with latitude and is very very low.
r_value:
    Northern : 0.04494842986737573
    Southern : -0.011173762440052987
![alt text](/images/NorthHumid.png)![alt text](/images/SouthHumid.png)
#### Latitude vs. Cloudiness
On both Northen and Southern Hemisphere there are very low correlation with cloudiness. R-value is very close to 0 on both Hemisphere.
r_value:
    Northern : -0.00878850018444309
    Southern : 0.033286983756034394
![alt text](/images/NorthCloud.png)![alt text](/images/SouthCloud.png)
#### Latitude vs. Wind Speed
There is very low negative correlation among Wind Speed and latitude on North and South Hemisphere. In Northern Hemisphere the speed in majority of the cities is between 0 and 10. In sothern Hemisphere wind speed slowly increases and it between 0 to 7.5.There is very little or no correlation between wind and Latitude.
r_value: 
    Northern : -0.11485974631628554
    Southern : -0.12048305924429477
![alt text](/images/NorthWind.png)![alt text](/images/SouthWind.png)

## Part2: VacationPy
    In this part, weather data skills has been used to plan a future vacations and I used Jupyter notebook, geoViews Python libarary, and Geoapify API. The project here is based on the cities that the coordinates has been created for each city in part1. Here I created map visualizations for all those cities. 
    the ideal weather condition that I look for are limited to these three factores : A max temperature lower than 27 degrees but higher than 21, Wind speed less than 4.5 m/s, and . Zero cloudiness


## Results VacationPy


## Refrences
Data has been retrieved from OpenWeatherMap API .