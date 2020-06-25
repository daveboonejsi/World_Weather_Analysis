# World_Weather_Analysis
Analysis of weather patterns for travel company

## part one
in the first part (Weather_database.ipynb) I used pandas and numpy to create a list of randomly selected pairs of latitudes and longituds.  I imported the requests module for python to enable api calls.  I obtained a API key from open weather map and imported the weather data for the selected latitudes and longitude pairs.  I created pandas dataframe from the json output from the api call, including information on rain and snow for each lat/long pair.  I then exported the data to a csv file (WeatherPy_Database.csv).


## part two
In part II (Weather_search.ipynb) I read in the WeatherPy_database.csv file and created a dataframe.  I created input variables for max and min temperature and the presence or absence of rain and snow.  I then filtered out cities with min temp of 60 and max temp of 90 with no rain or snow. I used Google API services to obtain hotel information wihtin 5000 meters using the API key obtained from Google.  I then outputted the hotel data to a csv file (WeatherPy_Vacation.csv).  

## Part three
In part three (Vacation_itinerary.ipynb) I imported the csv file WeatherPy_vaction.csv, created a template for the hotel marker information and linked the locations from the hotel data to the map using the lat/long pairs.  using the Google maps api, I created a map showing markers with the hotels

Images/WeatherPy_vacation_map.png
