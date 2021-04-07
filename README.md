# WeatherPy
## Overview of Project

### Purpose
To retrieve Weather Data using OpenWeatherMap API and create a customer travel destinations map and travel itinerary map using Google Maps APIs.

## Retrieval of Weather Data
Generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with the OpenWeatherMap. In addition to the city weather data gathered, API requests were used to retrieve the current weather description for each city. Then, a new DataFrame containing the updated weather data was created.

### Retrieved the following information from the API call:
    Latitude and longitude
    Maximum temperature
    Percent humidity
    Percent cloudiness
    Wind speed
    Weather description (for example, clouds, fog, light rain, clear sky)

## Creating a Customer Travel Destinations Map
Used input statements to retrieve customer weather preferences, then used those preferences to identify potential travel destinations and nearby hotels. Then, showed those destinations on a marker layer map with pop-up markers using Google Maps API.

![image](https://user-images.githubusercontent.com/5934390/113918683-b87a6780-97b0-11eb-9041-463ad0688008.png)

## Creating a Travel Itinerary Map 
Used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations.\

![image](https://user-images.githubusercontent.com/5934390/113918905-f5465e80-97b0-11eb-825a-547120e6e717.png)

Then, created a marker layer map with a pop-up marker for each city on the itinerary.
![image](https://user-images.githubusercontent.com/5934390/113918940-01322080-97b1-11eb-862a-238dc5af4708.png)
