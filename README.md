# Python API Challenge

This is an assignment I completed for the [UCSD Extension Data Science Bootcamp](https://bootcamp.extension.ucsd.edu/). This assignment was broken into two portions, WeatherPy and VacationPy.

## WeatherPy

In WeatherPy I used the [OpenWeatherMap API](https://openweathermap.org/api) to generate a list of random cities across the world with the following information: city name, latitude, longitude, maximum temperature, humidity, cloudiness, wind speed, country the city is in, and the date the API call requested the data.

I then took this information into a Pandas dataframe, pushed it into a csv file for later use, and plotted it with MatplotLib. I used linear regression to chart different maximum temperature, humidity, cloudiness, and windspeeds in cities. These charts were split into northern and southern hemispheres.


## VacationPy

After importing dependencies and libraries I pulled the data from the [Cities Compiled.csv](https://github.com/mrryanlittle/python-api-challenge/blob/master/WeatherPy/Cities%20Compiled.csv) file created in VacationPy from the OpenWeathMap API. Using this data I am able to specify the best cities for my ideal vacation based on weather parameters. I was able to do this using the [Google Maps API](https://cloud.google.com/maps-platform/). Using the Google Maps API also allowed me to add a heatmap layer of temperatures on the global map. Using pandas.copy() I took the relevant columns: City, Country, Latitude, and Longitude to a new Pandas dataframe with a Hotel Name Column added. I filled the Hotel Name column with locations listed as Logding in the Google Maps API that are within 5000 meters of the latitude and longitude coordinated linked to the city. Now I have a hotel to choose from in my ideal vacation location. 

## Tools Used

Python

MatplotLib

Google Maps API

Pandas

Jupyter Notebook

## Thank You for Reading My ReadMe!

Thank you for reading my readme, I am always looking for feedback and work. Feel free to message me on GitHub or LinkedIn if you would like to connect.

[GitHub](https://github.com/mrryanlittle) - [LinkedIn](https://www.linkedin.com/in/ryanlittle01/)