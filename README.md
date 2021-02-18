# python-api-challenge
UofM Bootcamp - Python API Homework - What's the Weather Like?
Part I - WeatherPy
The WeatherPy notebook includes Python script to visualize the weather of 500+ cities across the world, at varying distances from the equator. In order to do this, I used a simple Python library, the OpenWeatherMap API, and a some common sense to create a representative model of weather across world cities.

Part II - VacationPy
Using a csv created from Part I - WeatherPy, I created a heatmap that displays the humidity for every city from Part I. I then narrowed down the DataFrame to find the ideal weather conditions. Then I used Google Places API to find the first hotel for each city located within 5000 meters of my coordinates. Finally, I plotted the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
