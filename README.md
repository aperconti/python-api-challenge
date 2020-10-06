In this project, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a simple Python library, the OpenWeatherMap API, aswell as creating a representative model of weather across world cities.
The first thing I accomplished was creating a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

After each plot I added a sentence or two explaining what the code is and what its analyzing.

my second task was to run linear regression on each relationship,this time I separated them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots I explained what the linear regression is modeling such as any relationships.

Part II - VacationPy
I used jupyter-gmaps and the Google Places API for this part of the assignment.


I created a heat map that displays the humidity for every city from the part I of the homework.

Next I narrowed down the DataFrame to find my ideal weather condition. 


Dropped any rows that didn't contain all three conditions.


Used Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.


Plotted the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.

