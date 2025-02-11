```leaflet  
id: saulker  
### Lock pins so they can't be moved  
lock: true  
### If true, view of map will recenter as you zoom out.  
recenter: true  
### If true, disables mouse scroll for zomming in and out of a map. Button controls still work.  
noScrollZoom: true  
image: [[saulker_map.png]]
bounds: [[0,0], [2805.48, 2805.48]]  
height: 800px  
width: 95%  
### This sets where the map starts by default. Set it to the middle (half) of your bounds.  
lat: 1402.74  
long: 1402.74  
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map.  
minZoom: -2.5  
### Max zoom is 18.  
maxZoom: 1.5  
### Hover mouse over the Reset Zoom icon to see your current zoom level.  
defaultZoom: -1  
### How far it zooms in or out with each step. Can be in decimals.  
zoomDelta: 0.5  
### This is a string so can be any text. Change it to match your maps measurement scale.  
unit: meters  
scale: 1  
darkMode: false  
```