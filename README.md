# Zomato Geospatial Analysis
This project makes use of Zomato data to render a geospatial analysis in Python.
Zomato is a food delivery company that operates in some countries. The data we have is of a city in India called Bangalore. The data contains physical addresses of restaurants, ratings, website, location, contact details etc.

We explore the Data analysis life-cycle from extracting the raw data, to processing and transforming it to useful data through data cleaning techniques and finally creating maps to visualize the data (EDA).

The libraries and packgages explored include:
- numpy
- pandas
- geopy
- folium
- Nominatim
- geolocator

Tasks completed include:
- Extracting of Latitude and Longitude from data using restaurant location name and Nominatim tool under the geocoders library (geocoding)
- Using Structured Queries to get coordinates. This makes use of physical addresses instead of location names and passing a dictionary to geolocator
- Creating a heatmap to show where most restaurants are located in the Bangalore city using folium package
- Perform marker cluster analysis using FastMarkerCluster library
- Plotting all locations using marker and defining popups
- Creating heatmap to show highest average rated restaurants

Standard analysis techniques were used to manipulate the data such that we get useful information, e.g. calculating average rating of restaurants, changinf of data types, creating new dataframes and merging them, calculating frequency of restaurant locations in data etc.

