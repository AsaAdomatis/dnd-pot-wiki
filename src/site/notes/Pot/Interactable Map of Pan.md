---
{"dg-publish":true,"permalink":"/pot/interactable-map-of-pan/"}
---

# Map of the Continent of Pan
```leaflet  
id: ContenintOfPan ### Must be unique with no spaces  
image: [[Pan Hi-Rez.png]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [3072, 4096]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 55% ### Size of the leaflet embed in px on your screen  
width: 100% ### Size of the leaflet embed in your note  
lat: 1536  ### To center the map, make this half of the map height.  
long: 2048 ### To center the map, make this half of the map width.  
minZoom: -4 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -2.5 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 3 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: true ### marker
```

