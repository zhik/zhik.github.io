---
layout: default
title: projects
---

# Projects/Works

----------------

## NYCDOT

### Web Batch Geocoder [Python, Javascript]
![web batch geocoder demo](images/geocoder.gif)

* Using Geosupport to make a web interface for easy geocoding of large speadsheets.
* View and correct for Geocoding errors.
* View results in leafet and export as shapefiles.

### QGIS 3 Cyclomedia Plugin [Python]
![qgis 3 cyclomedia plugin demo](images/qgis-cyclomedia.gif)

* A Qgis 3 plugin for browsing Cyclomedia street view and tagging features

### Print Preview with OpenLayers [Javascript]
![print preview with openlayers demo](images/print-preview.gif)

* rotation of page
* map adjustments in preview window

### SIP Project viewer [Javascript]
![sip project viewer demo](images/sips.gif)

* Using Mapbox and chart.js to display queried data from GeoServer.
* Includes different views for other projects.

### Roadway Deterioration Prediction [Python, R, SQL, Javascript]

* Processing and generating datasets from ArcSDE using python (arcpy and pandas)
* Assisting in building a GWR model in R
* Displaying the model using Leaflet and D3.js

> ![estimation of the average rate](images/deter.gif)

> ex: estimation of the average rate of deterioration from historical data (matplotlib)

> ![sample view of prediction and historical ratings](images/deter_map.gif)

> ex: web view of the prediction and historical ratings 

### Python Script Catalog and Remote use [Sqlite, Python-Flask]
<!-- ![python script catalog web app](images/script1.png) ![python script catalog web app](images/script2.png) -->

* Catalogs various scripts for quick searches based on functions, and tags.
* Run scripts using shell processes with parameters from form input.  

----------------

## Remote Sensing

### Vegetation Index Visualization in the Sahara Desert [PostGIS, Nodejs-Express, Javascript]
![vegetation index web view](images/desert.gif)

* Using python to gather imagery, selecting areas of interest
* Calculating EVI2 using PostGIS
* Serving time series images and graph data using Leaflet and Chart.js

### Crowdsourcing mixed pixels to aid in spectral unmixing [PostGIS, Python-Flask, Javascript]
<!-- ![crowdsourcing mixed pixel web app](images/unmix.png) -->
* Dividing remotely sensed imagery into smaller areas using python, store on PostGIS database
* Serve areas to users, using Google maps API display and take crowdsourced material polygons
* Process material polygons to percentages for ground truthing in python and PostGIS

### [Bandmath](https://github.com/zhik/bandmath) [Python]
<!-- ![ndvi time lapse of a farm](images/farm.gif) -->
* automating band math with gdal
* creating time lapse with images

----------------

## GIS

### [A snapshot of New York City’s distribution of community gardens and funding resources](pdfs/cg.pdf)
![community gardens funding types over race](images/cg.png)
* Where NYC Department of Parks & Recreation capital funding and community gardens are, in comparison to demographic factors


### [Determining the optimal route for a Cross-Queens canal](pdfs/canal.pdf)
![different possible canal routes](images/canal.png)
* Using raster least-cost path, on different senerios and datasets (DEM, bus/subway, landuse, FAR, Roadbed)


----------------
## Hackathons

updating ... 