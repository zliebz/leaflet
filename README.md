# Visualizing Data with Leaflet

## Overview

In this exercise, I visualized a GeoJSON dataset, sourced from the United States Geological Survey, or USGS. The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. For the purpose of this exercise, I chose to visualize reported earthquakes within the past 7 days.

### Visualization

1. **Getting the data set**

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. I visited the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and picked a dataset to visualize. Upon selecting my dataset, I was able to access a JSON representation of the data.

2. **Importing & Visualizing the Data**

   I created a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

   * The data markers reflect the magnitude of the earthquake by their size and and depth of the earth quake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.

- - -
