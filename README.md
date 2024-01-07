# python-api-challenge

This activity is broken down into two deliverables, WeatherPy and VacationPy.

## Part 1: WeatherPy

For WeatherPy, I employed Python scripts in a Jupyter notebook to visualize weather patterns across 500 cities at varying distances from the equator. Utilizing Citipy, I determined city locations based on latitude and longitude, and the OpenWeatherMap API for importing weather information.

-    Started by generating random geographic coordinates and finding the nearest cities.

-    Fetched weather data using the OpenWeatherMap API for these cities.

-    Created scatter plots showing relationships like Latitude vs. Temperature, Humidity, Cloudiness, and Wind Speed. Example:

![ScatterPlot_1](https://github.com/MarcoN16/python-api-challenge/assets/150491559/e37540d3-6c38-42a0-a32c-8b40f04af8f4)

-    Conducted linear regression analysis for each relationship. Splitting plots into Northern and Southern Hemispheres for better analysis.

-    Explored relationships like Temperature, Humidity, Cloudiness, and Wind Speed against Latitude in both hemispheres. Example:
![Uploading ScatterPlot_2n.png…]()
![ScatterPlot_2s](https://github.com/MarcoN16/python-api-challenge/assets/150491559/98d7ff93-f1a3-40c9-8a38-c2f451fa5e45)



## Part 2: VacationPy

In VacationPy, I developed a code using Jupyter notebooks, the geoViews Python library, and the Geoapify API to analyze weather data and plan vacations based on specific weather characteristics.

-    Loaded weather and coordinates data for cities from a CSV file.

-    Utilized the Geoapify API and geoViews Python library to create map visualizations, with the point sizes indicating humidity levels.
![GeoView1](https://github.com/MarcoN16/python-api-challenge/assets/150491559/8e188692-e135-4441-9e60-dc694ee2218b)


-    Narrowed down the DataFrame to identify ideal weather conditions: temperature between 21 and 28 degrees, low wind speed, and zero cloud cover.

-    Created a new DataFrame, 'hotel_df,' to store city, country, coordinates, and humidity information.

-    Leveraged the Geoapify API to find the closest hotel within 10,000 meters for each city's coordinates and added this information to the map's hover message.
![GeoView2](https://github.com/MarcoN16/python-api-challenge/assets/150491559/53db4fc9-49d1-44ea-a1ea-7d246c63e928)



