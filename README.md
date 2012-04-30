##About

**qgis-openlayers-plugin** is a [QGIS](http://www.qgis.org/) plugin embedding OpenLayers functionality.

It allows you to add basemaps to QGIS from:

1. Google Physical, Google Streets, Google Hybrid, Google Satellite
1. OpenStreetMap
1. OpenCycleMap, OCM Landscape, OCM Public Transport
1. Yahoo Street, Yahoo Hybrid, Yahoo Satellite
1. Bing Road, Bing Aerial, Bing Aerial with labels
1. Apple iPhoto map
1. Stamen Toner/OSM, Stamen Watercolor/OSM, Stamen Terrain-USA/OSM

##Installation

Installation is simple in recent versions of QGIS, just go to:

* Start QGIS
* From the Plugins menu -> click Fetch Python Plugins menu item 
* Click "Add 3rd Party Repositories" in the repositories tab. It'll do some stuff.
* Search for and install "OpenLayers Plugin" in the Plugins tab. 
* Restart QGIS, and find your new menu under Plugins -> OpenLayers Plugin. 
* When you pan and zoom, QGIS will automatically update the linked basemap layer.

[Read more at indicatrix blog »](http://indicatrix.wordpress.com/2011/04/06/basemaps-in-qgis/)

**NOTE:** Minimum QGIS version seems to be 1.7.4?

Does not work with 1.7.0 due to missing OSGEO python dependencies.

##Attribution

If you include these basemaps in your final map layout, make sure to credit the original author.

##Extras

Need a basemap that reprojects out of web Mercator on the fly? Check out the "goodies" folder here.

## Bug tracker and Wiki

http://hub.qgis.org/projects/openlayers

## Plugin repository

http://build.sourcepole.ch/qgis/plugins.xml

##License

qgis-openlayers-plugin is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

<em>Copyright (c) 2010 Pirmin Kalberer & Mathias Walker, Sourcepole AG</em>