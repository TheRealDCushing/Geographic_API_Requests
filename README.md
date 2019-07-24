### Intro

I was tasked with using the citypy library in conjunction with Google's Open-Weather API to examine trends in weather data across a random selection of cities. I used Pandas, Numpy, Requests, Time, and Matplotlib in a jupyter notebook running Python 3.


### Method and Results

Citypy contained a large list of cities with latitude and longitude information, and city names. To turn this into something we could use in conjunction with the Google API, I initialized two lists, one of latitude and one for longitude. I then used Numpy to generate random (uniform) longitudes and latitudes to populate the lists. The citypy library found the nearest cities, and a function was written to append those found cities to the cities list. 
The Google API only requires the input of the name of the city within the search URL, so for each city in the city list, that city was plugged into the requests URL.
Scatterplots were then constructed to show the effect of geolocation on the weather factors of interest.

For more details, please refer to the .ipynb file.
