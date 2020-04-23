# GeoMapping with Leaflet

## Overview:
USGS earthquake data were mapped alongside tectonic plate data using JavaScript, HTML, API and Leaflet.

## Data:

The data used was 'all earthquakes from the past 7 days' extracted in JSON format from the United States Geological Survey, or USGS. The URL of this JSON and an API key were used to pull in the data. The tectonic plate data was pulled from https://github.com/fraxen/tectonicplates. 

## Workflow:

A map was created using Leaflet, which plots all of the earthquakes from the earthquake dataset based on their longitude and latitude. The tectonic plates were visualized alongside the seismic activity data. The magnitude of each earthquake was represented by the size and color. Earthquakes with higher magnitudes are larger and darker in color.

Three base maps were chosen to visualize the street, satellite, and dark views. The two  datasets were separated into overlays that can be turned on and off independently.

## Maps:

- Street Map

<img src="images/StreetMap.png" width="800">

- Dark Map

<img src="images/DarkMap.png" width="800">

- Satellite Map

<img src="images/SatelliteMap.png" width="800">