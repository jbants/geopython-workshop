# Doing Geospatial in Python

With a low barrier to entry and large ecosystem of tools and libraries, Python is the lingua franca for geospatial development. Whether you are doing data acquisition, processing, publishing, integration or analysis, there is no shortage of solid Python tools to assist in your daily workflows.

This workshop will provide an introduction to performing common GIS/geospatial tasks using Python geospatial tools such as OWSLib, Shapely, Fiona/Rasterio, and common geospatial libraries like GDAL, PROJ, pycsw, as well as other tools from the geopython toolchain. Manipulate vector/raster data using Shapely, Fiona and Rasterio. Publish data and metadata to OGC web services using pygeoapi, pygeometa, pycsw, and more. Visualize your data on a map using Jupyter and Folium. Plus a few extras in between!

The workshop is provided using the Jupyter Notebook environment with Python 3.

## Installation

```bash
curl -O https://codeload.github.com/geopython/geopython-workshop/zip/master
unzip master
cd geopython-workshop-master/workshop
# start the workshop
./geopython-workshop-ctl.sh start
# check the URL+token
./geopython-workshop-ctl.sh url
# open browser to resulting URL+token
# stop workshop
./geopython-workshop-ctl.sh stop
```
