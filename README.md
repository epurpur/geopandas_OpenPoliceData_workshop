```
Last updated 03/07/23
```
# PyCHO GeoPandas Workshop

Thanks for coming today! This workshop will be taught on March 22, 2023 for PyCHO (Charlottesville Python Users Group). In this workshop we will be working with Geospatial Data in Python. In the Python ecosystem there are many geospatial libraries available which make it easy to work with data that previously required a full-fleged GIS software like ArcGIS or QGIS. In today's workshop we will be working a lot with the Geopandas library and with several others too. 


## **About Me**

Erich Purpur

    Research Librarian for Science & Engineering
    epurpur@virginia.edu
    Brown Science & Engineering Library room I046


## GeoPandas
[GeoPandas](https://geopandas.org/en/stable/) is an open source project to make working with geospatial data in python easier. GeoPandas extends the datatypes used by [Pandas](https://pandas.pydata.org/) to allow spatial operations on geometric types. Geometric operations are performed by [Shapely](https://shapely.readthedocs.io/en/stable/). Geopandas further depends on [Fiona](https://fiona.readthedocs.io/en/latest/) for file access and [MatPlotLib](https://matplotlib.org/) for plotting.

The goal of GeoPandas is to make working with geospatial data in python easier. It combines the capabilities of pandas and shapely, providing geospatial operations in pandas and a high-level interface to multiple geometries to shapely. GeoPandas enables you to do operations in python that would otherwise require a GIS software like ArcGIS, QGIS, or spatial database such as PostgreSQL/PostGIS.

## Folium
[Folium](http://python-visualization.github.io/folium/) builds on the data wrangling strengths of python and the mapping strengths of [Leaflet.js](https://leafletjs.com/). Manipulate your data in python, then visualize it on a Leaflet map via Folium. Folium makes it easy to visualize data that has been manipulated in python on an interactive leaflet map. It enables the binding of data to a map for choropleth visualizations as well as passing rich vector/raster/HTML visualizations as markers on the map. The library has a number of built-in tilesets from OpenStreetMap, Mapbox, and Stamen, and supports custom tilesets with Mapbox.

## OpenPoliceData
[OpenPoliceData](https://github.com/openpolicedata/openpolicedata) is a python package that provides access to 288 (and growing) incident-level open datasets from police departments from around the United States. Datasets include traffic stops, use of force, officer-involved shootings, complaints, and other types of police interactions. 

Users request data by department name and type of data, and the data is returned as a pandas DataFrame. There is no need to manually find the data online or make API calls. 
