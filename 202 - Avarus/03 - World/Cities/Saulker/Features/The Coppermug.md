### Summary
A small inn and tavern, owned and run by [[Tansy Coppermug]]. It is the only inn and tavern in town, thus is home to much of the town's entertainment, and business. Games of [[Throne]] are always being played at the large round table in the front right corner. On the back right wall, is a small raised stage where the gnomish bard [[Hanlan Fargon]] frequently plays evening sets. 

If the players enter the Coppermug for the first time while the festival is *not* going on, read the following: 

> [!recite|bg-green] ‎ 
> Inside, is a quaint tavern. The building is filled with a warm orange glow, emanating from a hearth along the wall across from the door. The aroma of rich ales, salty fragrance of grilled fish, and the ever present musk of old wood. The floor is scattered by tables, some round, some squared, all fitted with various number of chairs. From the door, the room stretches around to the right. At the back, is the bar, where a young gnome woman works. To its right is a small raised stage, to the left is a fireplace, and at the front right corner is a round table where cards are being played.

```leaflet  
id: coppermug_inn
### Lock pins so they can't be moved  
lock: true  
### If true, view of map will recenter as you zoom out.  
recenter: true  
### If true, disables mouse scroll for zomming in and out of a map. Button controls still work.  
noScrollZoom: true  
image: [[map_coppermug.inn.png]]
bounds: [[0,0], [1400, 1225]]  
height: 900px  
width: 95%  
### This sets where the map starts by default. Set it to the middle (half) of your bounds.  
lat: 907.53  
long: 1402.74  
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map.  
minZoom: -1.5  
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

### Services
#### Inn
* Room
	* Normal (1sp/day)
	* Large (2sp/day)
#### Tavern
* Drinks
	1. ale (4cp)
	2. mead (5cp)
	3. red wine (7cp)
	4. beer (4cp)
	5. whiskey (5cp)
	6. [[Embrelead]] (8cp)
* Food
	1. Mutton chops (6cp)
	2. Rabbit stew (6cp)
### Areas
#### A1. Storage Room
A small storage room. Clean, dimly lit by torches on either side of the room. 

##### Features
* Along the wall to the right of the door, is a row of **8 large kegs**, 1ft radius. The kegs contain, (in order from the door to the far wall.) 
	* **Kegs 1, 2.** ale
	* **Keg 3.** mead
	* **Keg 4.** red wine
	* **Keg 5, 6.** beer
	* **Keg 7.** whiskey
	* **Keg 8.** [[Embrelead]]
* Along the wall to the left of the door, are **large shelves** containing a myriad of items, some of which are as follows.
	* **Baskets.** apples, potatoes, onions, carrots, cabbage
	* **Wrapped.** fish, mutton, chicken
	* **Hand Kegs.** black pepper, salt, cloves, mace, dill

#### A2. Bar
The bar stretches from the edge of the *storage room*, across and up to the back wall. The outer length is fitted with backless chairs. When a player approaches the counter for the first time, read aloud.

> [!recite|bg-green] ‎ 
> The counter is dark walnut wood, appearing to be taken care of quite intensely. It bears a few small scratches, and a couple minor burn marks, but any major damage has since been repaired, and all spills, or other grime is quickly dealt with.

##### Features
* Under the counter.
	* various bottles of alcohol
	* some spices
	* an array of different cups, bowls, plates and eating utensils
* The back wall is lined with **shelves**, containing various items, most look to be decorative.
	* some **unique dishes**, painted or molded in interesting ways
		* *plate* molded in the shape of a flower
		* glass *plate* with a orange and blue offset swirls, approaching the center 
		* *cup* molded and painted like a leather shoe
		* tall cylindrical *cup*, painted like a tree trunk 
		* *skewer* shaped like a pale blue swordfish, the body the handle and, the nose the skewer
	* other **unique items**
		* *parchment*

#### A3. Sitting/Dining Area
Divided into two sections.

##### Sections
* The section of which the door leads directly into, is a small dining area, filled with large round tables, and two large booths, in each of the back corners. 
	* This is the quiet area, low conversations are carried, and various groups of people having meals. 
	* Business is constantly being carried out here, in the light of a flickering fireplace on the back wall.
* The second section is the bar
	* In the back corner, a stage is raised 1-foot high. The gnomish bard [[Hanlan Fargon]] frequently plays, predominantly in the evenings.
	* A table along the staircase to the upper floor, is a large round table where games of [[Throne]] are frequently played. A human woman named [[Gaela]] frequently runs these games.

#### A4. Stage
A 1-foot tall stage, a small set of stairs on the side, and a faded red curtain on its back wall. [[Hanlan Fargon]] plays most nights here.

#### A5. Patio


***
#### B1, B2, B3, B4. Bedroom
#### B5. Hall
#### B6. Sitting Area

***
#### C. Cellar (no map)
A small cellar area, with a hole cut into one of the walls.
##### Features
* Desk
* Hidden Room
	* A small room, dug into the wall, hidden by a bookshelf
	* A **DC 12 wisdom (perception)** check, reveals there is a small gap between the wall and bookshelf
	* A **DC 10 strength** check, allows the player to move  the bookshelf out of the way
	* There is a single chest in the room, it is unlocked inside is.
		* A fine leather shoe a **DC 12 intelligence (investigation)** check reveals the name *cobbs* with the emblem of a stone on the bottom of the sole
		* A pouch of 5gp
		* A map of Sodavar, with two locations circled, a city called *'Helrich'*, and an area or forest north-west of Helrich.
* Crates
	* There are four crates stacked in the corner of the room.
	* One is open, and empty.
	* One is open, has wrapped salted meats.
	* One is closed a **DC 15 strength** check opens it, has bottles of [[Embrelead]].
	* One is closed a **DC 15 strength** check opens it, has various fruits.
		* Pears
		* Apples
		* Peaches
		* Apricots
		* A **DC 16 intelligence (investigation)** check reveals a yellow apple
			* **DC 14 intelligence (arcana)** check reveals the apple is magical, but not how so
			* **DC 15 intelligence (nature)** check reveals this apple is from the Feywild
			* Eating the apple will satiate the player's hunger for 2 full days

### Keyed Locations
#### II. Throne Table

### Relevant Characters
#### [[Tansy Coppermug]]
**Role.** Owner, head bartendress.

#### [[Hanlan Fargon]]
**Role.** Bard, plays sets almost every night.

### History
The coppermug was originally owned by [[Knowen Ore]], a human man.