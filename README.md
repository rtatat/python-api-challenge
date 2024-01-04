# python-api-challenge

For this challenge, two major tasks need to be completed, the first being an analysis on the weather of more than 500 cities and the second being to determine potential vacation locations based on the desired parameters.

For the first task, called WeatherPy, I needed to:
1. Randomly generate a large list of random cities using openweatherAPI based on latitudes and longitudes. Then generating the maximum temperature, humidity, cloudiness, wind speed, country and date information, and then placing all of this information into a dataframe
2. Scatter plots were created to showcase the relationships between latitude and temperature, humidity, cloudiness and windspeed
3. A linear regression was generated for each of these relationships, with each relationship being further specified by the hemisphere that the cities are located in. Then an analysis was conducted based on the results generated

For the second task, called VacationPy, I needed to:
1. Import the list of cities and their associated weather and location data from the WeatherPy task
2. Create a map for all of those cities and ensure that the size of each point on the map is scaled towards their respective humidities
3. Restrict the total number of cities to a select few based on specific desired criteria. I desired cities with a maximum temperature between 19 and 30 degrees inclusive, a cloudiness of more than 30, a humidity less than or equal to 75 and a wind speed of more than 3 m/s
4. A new dataframe was generated to store the first hotel found within a 10km distance from the city using Geoapify API and a new map was generated to show all of the desired cities with their closest hotels and humidities
