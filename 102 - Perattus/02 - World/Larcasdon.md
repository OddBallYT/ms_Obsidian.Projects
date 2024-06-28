```leaflet  
id: Larcasdon_map 
### Lock pins so they can't be moved  
lock: false  
### If true, view of map will recenter as you zoom out.  
recenter: true  
### If true, disables mouse scroll for zomming in and out of a map. Button controls still work.  
noScrollZoom: false  
image: [[Perattus Map.png]]
bounds: [[0,0], [5075, 3858]]  
height: 900px  
width: 95%  
### This sets where the map starts by default. Set it to the middle (half) of your bounds.  
lat: 1929
long: 2537.5  
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map.  
minZoom: -4  
### Max zoom is 18.  
maxZoom: 1.5  
### Hover mouse over the Reset Zoom icon to see your current zoom level.  
defaultZoom: -2.5
### How far it zooms in or out with each step. Can be in decimals.  
zoomDelta: 0.5  
### This is a string so can be any text. Change it to match your maps measurement scale.  
unit: meters  
scale: 1  
darkMode: false
```