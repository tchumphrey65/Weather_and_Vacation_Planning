# Weather_and_Vacation_Planning
## Weather analysis, vacation city selection using OpenWeather and Google APIs

## Overview of Projects

The task we have been assigned is to perform three technical analyses.

### 1: Retrieve Weather Data
#### Deliverable 1 Requirements
  - Generate a set of 2,000 random latitudes and longitudes.
  - Retrieve the nearest city.
  - Perform an API call with the OpenWeatherMap.
  - Obtain city weather data including current weather description for each city.
  - Create a new DataFrame containing the updated weather data.

### 2: Create a Customer Travel Destinations Map
#### Deliverable 2 Requirements

  - Use input statements to retrieve customer weather preferences
  - Use those preferences to identify potential travel destinations and nearby hotels.
  - Show those destinations on a marker layer map with pop-up markers.

### 3: Create a Travel Itinerary Map
#### Deliverable 3 Requirements

  - Choose 4 cities possible travel destinations,
  - Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen.
  - Create a marker layer map with a pop-up marker for each city on the itinerary.

## Resources
  - Data Source: WeatherPy_Database.csv; WeatherPy_vacation.csv
  - Python Code: Weather_Database; Vacation_Search; Vacation_Itinerary
  - Software: Python 3.7.11 64-bit (conda); jupyter-notebook; 
  - APIs: openWeatherWeather API (https://openweathermap.org/api); Google Maps APIs


## Results
### Weather Database
The following has been created and stored in the Weather_Database folder:

  - Generate a set of 2,000 random latitudes and longitudes
  - Retrieved nearest city to latitudes and longitudes
  - Executed an API call using OpenWeatherMap API
  - Retrieved current weather information including weather description for each city.
  - Created a DataFrame containing the updated weather data and printed to csv file
   https://github.com/tchumphrey65/Weather_and_Vacation_Planning/blob/main/Weather_Database/weatherPy_database.csv

### Vacation Search
The following has been created and stored in the Vacation_Search folder:

  - Used input statements to retrieve customer weather preferences.
  - Used input preferences to select matching travel destinations and identify nearby hotels.
  - Exported a CSV of possible vacation locations meeting inpute weather criteria
  https://github.com/tchumphrey65/Weather_and_Vacation_Planning/blob/main/Vacation_Search/weatherPy_vacation.csv
  - Display identified destinations on a Google map using marker layer showing pop-up markers.

![Vacation City Maps with Markers](https://user-images.githubusercontent.com/91839403/148290338-fc53dda8-a032-4617-a553-bb4594098e0f.png)


### Vacation Itinerary
The following has been created (Vacation_Itinerary folder):

  - Created travel itinerary using Google Maps API direction layer showing the route between four cities selected from list of possibilibities from Vacation_Search 
  - Add a pop-up marker using Google Maps API Marker Layer for each selected city in the proposed itinerary
  - Created map of vacation possible destinations with pop us markers including current weather.

![Vacation_Itinerary](https://user-images.githubusercontent.com/91839403/148291810-eb50d73e-bc02-4999-94db-e56e071324f9.png)

![WeatherPy_travel_map](https://user-images.githubusercontent.com/91839403/148291849-38421731-104b-41f1-8235-2d4803f2ddf5.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/91839403/148291910-91dbe571-5132-45ed-9609-ed700521633b.png)





