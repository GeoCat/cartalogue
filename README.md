Cartalogue
==========

Cartalogue is a client for spatial catalogues. Currently the app can only do queries against 
recent versions of Geonetwork OpenSource (CSW not supported yet)
Mind that the map currently only supports a spherical mercator projection (aka epsg:900913). 
WMS-ses not supporting this projection can not be displayed (and no warning is displayed).

Cartalogue was founded by GeoCat bv, Bennekom. The code is on github using an MIT license. 
		
Cartalogue is using following Open Source components:

	- Jquery mobile
	- Cordova
	- LeafletJS
	- Geonetwork-opensource

Any comments can be send to <a href="mailto:support@geocat.net">support@geocat.net</a>.

The app can be compiled into android/ios/win-phone using phonegap

Adjust settings.js to meet your environment, be sure to get an account at cloudmade.com or any other 
background tile provider (osm.org, mapbox.com, google.com, nokia)

The app can also run as a mobile website, in that case you need to add a proxy script