# Trip-Planning-Using-Google-Maps-API
Retrieve weather data for different cities near certain co-ordinates using an API call with OpenWeatherMap (See Weather_Databse folder)
Use input statements to filter the data for weather preferences, which will be used to identify potential travel destinations and nearby hotels.From the list of potential travel destinations, user choose four cities to create a travel itinerary (See Vacatoin_Search folder).
Finally, using the Google Maps Directions API, the program will create a travel route between the four cities as well as a marker layer map(See Vacation_itinerary folder).

# What Weather_Database_Challenge.ipynb does?
Generates a set of 2,000 random latitudes and longitudes, retrieves the nearest city, and performs an API call with the OpenWeatherMap. In addition to the city weather data gathered in this module, it uses the API to retrieve the current weather description for each city and creates a new DataFrame containing the updated weather data and it saves the data frame in a csv file

# What Vacation_Search_Challenge.ipynb does?
Uses input statements to retrieve customer weather preferences(filtering dataframe using the user input), then uses those preferences to identify potential travel destinations and nearby hotels(using Google Nearby Search). Then, show those destinations on a marker layer map with pop-up markers(includes Hotel name, city, country and max temperatrure and current weather description).

# What Vacation_Itinerary_Challenge.ipynb does?
Imports the vacation CSV file. From the map picks 4 cities that are in close proximity that the customer would travel to and creates a directions layer map. Takes screenshot of the route and saves it. Then creates a marker layer for the four cities. Each city has a pop-up marker that contains The hotel name The city The country The current weather description and the maximum temperature
