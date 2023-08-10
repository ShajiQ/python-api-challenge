# python-api-challenge
WeatherPy
I first imported libraries to generate a random geographic coordinates and a list of cities.
There were 620 cities in the list

I then created plots to showcase the relationship between weather variables and latitude using OpenWeatherMap API

I then created a scatter plot comparing the following:
  Latitude vs Temperature which showed that as the latitude approached 0 the temperature rose higher. 
  Latitude Vs. Humidity which showed that there was no significant relationship between the two variables.
    Latitude Vs. Cloudiness which showed no significant relationship between the two variables. 
      Latitude vs Wind speed which showed no significant relationship between the two variables. 

I then created a linear regression for each relationship. 
The linear regression suggests a negative correlation between latitude and max temperature in the Northern Hemisphere.
The linear regression suggests a positive correlation between latitude and max temperature in the Southern Hemisphere.
The linear regression suggests a weak linear relationship between latitude and humidity in the Northern Hemisphere.
The linear regression suggests a weak linear relationship between latitude and humidity in the Southern Hemisphere.
The linear regression suggests a very weak or no significant linear relationship between latitude and cloudiness in the Northern Hemisphere.
The linear regression suggests a very weak or no significant linear relationship between latitude and cloudiness in the Southern Hemisphere.
The linear regression suggests a very weak or no significant linear relationship between latitude and wind speed in the Northern Hemisphere.
The linear regression suggests a very weak or no significant linear relationship between latitude and wind speed in the Southern Hemisphere.

The next assignment in VacationPy i used the starter code to import libraries and load the weather and coordinates data. 
  I first created a map that displays a point for every city in the data frame. The size of the point was relative to the humidity in each city. 
  I then created a data frame that found cities with my ideal weather condition. 
  I then created a new data frame to narrow down the hotels. 
  Next I created a data frame using Geoapify API to find the first hotel located within 10,000 meteres of my coordinates. 
  Finally I created a map to display these cities. 
