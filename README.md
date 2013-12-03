gibs-web-examples
===============

This project shows how to use [GIBS](https://earthdata.nasa.gov/gibs) as a tile
source for [OpenLayers 2](http://openlayers.org) and
[Leaflet](http://leafletjs.com).

Live Examples
--------------------

* OpenLayers 2
 * [Geographic (EPSG:4326)](https://earthdata.nasa.gov/gibs/examples/openlayers2/EPSG4326.html)
 * [Arctic (EPSG:3413)](https://earthdata.nasa.gov/gibs/examples/openlayers2/EPSG3413.html)
 * [Antarctic (EPSG:3031)](https://earthdata.nasa.gov/gibs/examples/openlayers2/EPSG3031.html)
* Leaflet
 * [Geographic (EPSG:4326)](https://earthdata.nasa.gov/gibs/examples/leaflet/EPSG4326.html)
 * [Arctic (EPSG:3413)](https://earthdata.nasa.gov/gibs/examples/leaflet/EPSG3413.html)
 * [Antarctic (EPSG:3031)](https://earthdata.nasa.gov/gibs/examples/leaflet/EPSG3031.html)

Overview
-------------
Clone the repository and open the index.html file in your browser.


OpenLayers 2
-------------------
This example uses [OpenLayers](http://openlayers.org) version 2.13.1.

Due to a bug in OpenLayers, shearing in the map may occur when using Internet
Explorer.

To properly support the polar projections,
[proj4js](http://trac.osgeo.org/proj4js) must be included. This example uses
proj4js version 2.0.0.

Leaflet
---------
This example uses [Leaflet](http://leafletjs.com) version 0.6.4.

To properly support the polar projections, the
[Proj4Leaflet](https://github.com/kartena/Proj4Leaflet) plugin must be
installed. This example uses Proj4Leaflet version 0.6.2.

The version of  [proj4js](http://trac.osgeo.org/proj4js) shipped with
Proj4Leaflet is too old and must be replaced with version 2.0.0.

Questions
-------------
Send questions or comments to
[support@earthdata.nasa.gov](mailto:support@earthdata.nasa.gov)
