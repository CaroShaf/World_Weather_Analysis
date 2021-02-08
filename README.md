# World_Weather_Analysis

## Overview of the world weather analysis:
This project was designed to analyze weather data for the MyTripPlan app, and also to help the middle school STEM class project, with visualizations of statistical weather data relationships and for customer trip planning purposes.  Not only can customers see locations with the range of temperatures of their preference, with nearby hotels, but a suggested 4-city driving tour/travel itinerary is provided, based on their preferences.

First, a database of cities was created using random numbers to generate latitude and longitude.  The Citipy dependency features a function which provides the nearest city to latitude and longitude coordinates, which this database is checked against.  Weather data for each pair of coordinates for each city is obtained from an API call to openweathermap.org.  A customer can enter their max and min preferred temperatures and cities which match their request are matched up with the cities in our database.

Resources utilized:  Python 3.7.9, Pandas library, Jupyter Notebook, Conda Python environment, Excel 365 (to view CSV files), CitiPy, Numpy, Matplotlib, openweathermap API, Google maps and places (gmaps), and Directions APIs, Requests library

## Results
Beta testers have given this app good reviews.  They also asked for the additional feature of providing a suggested four-city travel plan that matches their requested temperature range.  This feature as well as pop-up boxes on city markers give some compelling suggestions for the user.

The graphs provided to the middle school included temperature, humidity, cloudiness and wind speed versus latitude.  The correlation was strong between latitude and temperature,
but not strongly correlated on other weather variables.

## Summary
Many different libraries and APIs can be used to pull together useful information in a simple and appealing interface for the purpose of making travel plans and understanding weather patterns throughout the year around the globe.
