# Leaflet 2GIS plugin

This plugin add 2GIS support to [Leaflet](https://leafletjs.com/).

## Requirements

* Leaflet 0.6 or newer
* 2GIS api library (see example)

## Demo

See the [demo](http://emikhalev.github.io/leaflet-2gis/).

## Usage

```javascript
var map = new L.Map("map", {
	center: new L.LatLng(54.99014, 73.365319), 
	zoom: 10,
	zoomAnimation: true 
});
var dgis = new L.DGis();
map.addLayer(dgis);
```

## License
Leaflet 2GIS (2013-2014 by Eugene Mikhalev) is [free software](https://www.gnu.org/philosophy/free-sw.html), and may be redistributed under the MIT LICENSE.
