# python-api-challenge
Explore weather based on geographic location and find accommodations based on those results using various APIs

WeatherPy

Pulls a list of ~600 random cities. Coordinates are pulled using the OpenWeatherMap geolocation API. This is then used to pull the weather (Temp, Humidity, Cloudiness, and Wind Speed) from each city.
Data is cleaned and compiles into a DataFrame. Various scatter plots and linear regression modeals are created to compare latitude to temp, humidity, cloudiness, and wind speed. DataFrame is stored for use in VacationPy.

VacationPy

Cities are plotted on a map. Markers are scaled based on local humidity levels. DataFrame is narrowed down to meet specifications (temp between 21C and 27C, Wind speed less than 4.5 m/s, Zero cloudiness)
This reduced dataset is used to pull and store the names of the nearest hotel accomdation in each city. This is retrieved from the GeoApify API. This new dataset is then mapped.
