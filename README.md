# UAF GINA / AK EPSCoR ACE

## Cesium Demo : Historical imagery and change detection

This is a demonstration created to explore using the [cesium]() tool kit to do web visualiation of histoircal imagery and lake change detection for the NSF EPSCoR Alaska Adapting to a Changing Environment (EPSCoR ACE) project.

The imagery datasets visualizaed here are:
* 1950's historical imagery by the USGS
* 1980's historical Alaska High Altitutde Photogrammitry project imagery
* current imagery layers

Layerd in here is a lake change detection dataset created for the EPSCoR ACE Northern Test Case.  Using the historical imagery lakes from the three different eras were mapped to allow lake changes to be detected and better understood.

This Cesium web interface was an exploration by a summer intern, Khan Howe, into how to use the Cesium toolkit to bring in imagery web services and the lake change datasets done by other summer interns into a web visualizatoin environment.


### HOW TO's:
You can access the web demo by going to:
https://ak-nsf-epscor.github.io/ace-cesium-demo/Cesium/Apps/viz.html

Operation should be intuitive, as it behaves about the same as google earth/maps.

The buttons at the bottom of the screen activate funtions. These functions will either place your viewpoint onto a specific area, load in data or tiles, or both.

The full screen button is in the bottom right hand corner.

If you're using a VR device such as the Oculus Rift or Google Cardboard, click the glasses button for VR mode.

The bottom left hand corner features time control settings. You should be able to see the earth rotate if you zoom out enough. 

This demo was made with Cesium JavaScript functions and some basic HTML. The Cesium function documentation can be found here: https://cesiumjs.org/Cesium/Build/Documentation/index.html


CREDITS:
This demo uses multiple sources of geographic tiles and information provided by GINA.

The world map tiles can be found here: http://tiles.gina.alaska.edu/tiles/info/bdl

The 1955 Northern Test Case Aireal Imagery tiles can be found here: http://tiles.gina.alaska.edu/tiles/info/epscor_ntc_epscor_northern_historical_usgs_1955_geo

Outlines of the Northern Test Case Lakes provided by Roberta Walker can be found in a GeoJson format here: https://alaska113.github.io/lakes.txt


FUTURE WORK:
-If someone were to create a union between this demo and the Unity demo, it would be a very powerful tool. My original plan after experimenting with both was to have an area selection and display tool made with Cesium that then creates a 3D surface terrain map on unity. I unfotunatly could not make it to this step.

-Waiting on a 3857 web mercator projection for 1982 data. 

-HTML buttons function as on-off switches rather than just on.

-A better interface and live updated information would be a great use of Cesium. An example of this type of interface can be found here: http://science.nasa.gov/iSat/?group=SMD

-Load in more interesting data provided by GINA, EPSCoR, and their partners. This could include historical climate data, geographic data, etc. 

Demo created by GINA intern, Khan Howe. Thanks very much to the entire GINA office, especially to Dayne, Jay, and Vanessa for helping me through the proccess. 
