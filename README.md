# python-api-challenge
## Part1: WeatherPy
    I created the Python script to visualize weather of over 500 cities of varying distances from the equator. In this activity I created some scatter plots to showcase the relationship between weather variables and latitude, plus I computed Linear Regression for each relationship. 

    The scatter plotes series wich will showcase here are include four different relationships, such as Latitude vs. Temperature, Latitude vs. Humidity, Latitude vs. Cloudiness, and Latitude vs. Wind Speed. 

    Linear regression has been computed for each relationship. The plots has been separated into Northern Hemisphere and Southern Hemisphere. 

### Results WeatherPy
#### Latitude vs. Temperature
Correlation among Max Temperature and Latitude in Northern Hemishphere is negative and the higher the Latitude the lower Temperature. Correlation among Max Temperature and Latitude in Sothern Hemisphere shows a positive relation and with increase of the Temperature the Latitude goes up.
r_value:
    Northern : 0.6409014602340861
    Southern : 0.8318082534886896


<img src="/images/NorthTemp.png" width="200"/>
<img src="/images/SouthTemp.png" width="200"/>


#### Latitude vs. Humidity
orthern Hemisphere Latitude has a low positive correlation with humidity the increase latitude cause the humidity goes slowly higher. Sothern Hemisphere Humidity has a negative relation with latitude and is very very low.
r_value:
    Northern : 0.04494842986737573
    Southern : -0.011173762440052987

<img src="/images/NorthHumid.png" width="200"/>
<img src="/images/SouthHumid.png" width="200"/>


#### Latitude vs. Cloudiness
On both Northen and Southern Hemisphere there are very low correlation with cloudiness. R-value is very close to 0 on both Hemisphere.
r_value:
    Northern : -0.00878850018444309
    Southern : 0.033286983756034394

<img src="/images/NorthCloud.png" width="200"/>
<img src="/images/SouthCloud.png" width="200"/>


#### Latitude vs. Wind Speed
There is very low negative correlation among Wind Speed and latitude on North and South Hemisphere. In Northern Hemisphere the speed in majority of the cities is between 0 and 10. In sothern Hemisphere wind speed slowly increases and it between 0 to 7.5.There is very little or no correlation between wind and Latitude.
r_value: 
    Northern : -0.11485974631628554
    Southern : -0.12048305924429477

<img src="/images/NorthWind.png" width="200"/>
<img src="/images/SouthWind.png" width="200"/>


## Part2: VacationPy
    In this part, weather data skills has been used to plan a future vacations and I used Jupyter notebook, geoViews Python libarary, and Geoapify API. The project here is based on the cities that the coordinates has been created for each city in part1. Here I created map visualizations for all those cities. 
    the ideal weather condition that I look for are limited to these three factores : A max temperature lower than 27 degrees but higher than 21, Wind speed less than 4.5 m/s, and . Zero cloudiness


### Results VacationPy
The city map has been created to display a points of every city in city_data_df DataFrame. 

<img src="/images/CityMap.png" width="500"/>

Data has been narrowed down to display ideal weather condition. The conditions are include: A max temperature lower than 27 degrees but higher than 21,Wind speed less than 4.5 m/s, and Zero cloudiness.

I used Geoapify API to find the first hotels within 10,000 meters of the city coordinates. 

<img src="/images/HotelNamesDF.png" width="500"/>

Added the hotel name and the country as additional information in the hover message for each city in the map.

<img src="/images/HotelMap.png" width="500"/>






## References
Data has been retrieved from OpenWeatherMap API , and Geoapify API used to find hotels. 