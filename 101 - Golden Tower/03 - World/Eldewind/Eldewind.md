### Summary
Eldewind is one of the various [[Realm|realms]] throughout the world. It is the western-most realm of the known world, and the primary setting of the Golden Tower novel series. It was founded 9tO/San/1EoE.
```leaflet  
### Tutorial: [https://youtu.be/54EyMzJP5DU](https://youtu.be/54EyMzJP5DU)  
### id must be unique  
id: map-eldewind
image: map-eldewind.png
height: 500px  
width: 100%  
### This sets where the map starts by default. Set it to the middle (half) of your bounds.  
lat: 50  
long: 50  
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map.  
minZoom: 0  
### Max zoom is 18.  
maxZoom: 18  
### Hover mouse over the Reset Zoom icon to see your current zoom level.  
defaultZoom: 15  
### How far it zooms in or out with each step. Can be in decimals.  
zoomDelta: 0.5  
### This is a string so can be any text. Change it to match your maps measurement scale.  
unit: miles
scale: 1  
darkMode: false  
```

### Map
```leaflet
id: map-eldewind
image: [[map-eldewind.png]]  
height: 1000px  
width: 100% 
lat: 50  
long: 50 
minZoom: 14
maxZoom: 18
defaultZoom: 16  
zoomDelta: 0.5 
unit: miles  
scale: 1  
darkMode: false
```
