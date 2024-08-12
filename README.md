# python-challenge-api

WeatherPY

This code creates a series of scatter plots, from the listed cities, showcasing the relationship between the following:
  - Latitude vs. Temperature
  - Latitude vs. Humidity
  - Latitude vs. Cloudiness
  - Latitude vs. Windspeed

The code also shows the linear regressioin for each relationship. 

VacationPy

This code creates a map showing all the cities from WeatherPy witht the size of the point being the humidity on that day. 
I have also filtered out cities with the ideal conditions of a max temperature lower than 27 degrees but higher than 21 degrees. A windspeed of less than 4.5 m/s and zero cloudiness. With the new dataframe showing the ideal cities, a map was created showing the first hotel listed within 10,000 meters of the cities coordinates. 


Credits:
Code was created using classwork. The hotel map with the hover feature was created using https://stackoverflow.com/questions/59678780/show-extra-columns-when-hovering-in-a-scatter-plot-with-hvplot
