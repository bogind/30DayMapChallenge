# 30 Days Map Challenge 2021 (Pokemon Edition)
Each map will use a different color palette from the [Pokemon Color Palettes](https://plugins.qgis.org/styles/103/) for QGIS available in QGIS HUB.  
All maps, unless stated otherwise, are made using only QGIS.

|Day|Date|Theme|Done|Ideas|Color palette|
|---|----|-----|----|-----|-------------|
1|01-11-2021|Points|&check;|Coutries whose centroids are disjoint|Abra|
2|02-11-2021|Lines|&check;|San Francisco roads (OSM)|Nidorina|
3|03-11-2021|Polygons|&check;|San Francisco buildings (OSM)|Nidorino|
4|04-11-2021|Hexagons|&check;|Hexagons of population, South America|Pikachu|
5|05-11-2021|Data challenge 1: OpenStreetMap|&check;|A literal streep map|Onix|
6|06-11-2021|Red|&check;|London - Buildings, Railroads, Greenspaces|Charmander|
7|07-11-2021|Green|&check;|London - Buildings, Railroads, Greenspaces|Bulbasaur|
8|08-11-2021|Blue|&check;|London - Buildings, Railroads, Greenspaces|Squirtle|
9|09-11-2021|Monochrome|&check;|Rivers & Lakes in North America|Ditto|
10|10-11-2021|Raster|&check;|Mars DEM|Gastly|
11|11-11-2021|3D|&check;|Extruded Buildings Tel Aviv, by OSM height\levels|Porygon|
12|12-11-2021|Population|&check;|Urban Centers Population Growth in Great Britain|Victreebell|
13|13-11-2021|Data challenge 2: Natural Earth|&check;|Just a bunch of Natural Earth layers|Nidoqueen&Nidoking|
14|14-11-2021|Map with a new tool|&check;|San Francisco elevation hexagons|Venusaur|
15|15-11-2021|Map made without using a computer||||
16|16-11-2021|Urban/rural||||
17|17-11-2021|Land||||
18|18-11-2021|Water||||
19|19-11-2021|Island(s)||||
20|20-11-2021|Movement||Honeymoon road trip?||
21|21-11-2021|Elevation||Isle of Skye Tanaka Contours||
22|22-11-2021|Boundaries||||
23|23-11-2021|Data challenge 3: GHSL Global Human Settlement Layer||Urban Centre Database UCDB R2019A ||
24|24-11-2021|Historical map||||
25|25-11-2021|Interactive map||||
26|26-11-2021|Choropleth map||||
27|27-11-2021|Heatmap||||
28|28-11-2021|The Earth is not flat||globe with stars||
29|29-11-2021|NULL|||missingNo|
30|30-11-2021|Metamapping day||Blog Post||

## Map 1 - Points

A map showing the centroids (and polygons, I'm not a monster) of all the countries that do not contain their centroids,   
meaning the center of the country is outside of its borders.   
The maps background and features are styled using the **Abra** color palette.  


<img src="1-Points(Abra).png" alt="1-Points(Abra)" width="60%"/>

## Map 2 - Lines

Maps 2 and 3 belong to the same project, except for the roads layer in map 2 and the buildings layer in map 3 they are the same.  
The switch in symbology is done using map themes and an expression that check if a specific layer is visible.  
Map showing the roads in San Francisco, California, United States, Clipped to the shape of the pokemon **Nidorina** hiding in tall grass.  
Clipping was done with a traced polygon in the map layout, and background created with a random marker fill over a white simple fill.   
The maps background and features are styled using the **Nidorina** color palette.  


<img src="2-Lines(Nidorina).png" alt="2-Lines(Nidorina)" width="60%"/>

## Map 3 - Polygons

Maps 2 and 3 belong to the same project, except for the roads layer in map 2 and the buildings layer in map 3 they are the same.  
The switch in symbology is done using map themes and an expression that check if a specific layer is visible.  
Map showing the buildings in San Francisco, California, United States, Clipped to the shape of the pokemon **Nidorino** hiding in tall grass.  
Clipping was done with a traced polygon in the map layout, and background created with a random marker fill over a white simple fill.   
The maps background and features are styled using the **Nidorino** color palette.  


<img src="3-Polygons(Nidorino).png" alt="3-Polygons(Nidorino)" width="60%"/>

## Map 4 - Hexagons

Map showing South Americe split into hexagons 50km high and wide anc colored by population estimate,   
without a legend because the colors have exactly 0 meaning and the ramp is not graduated.    
The grid was created in QGIS and then connected to a Natural Earth countries layer through a spatial join.  
The maps background and features are styled using the **Pikachu** color palette.

<img src="4-Hexagons(Pikachu).png" alt="4-Hexagons(Pikachu)" width="60%"/>

## Map 5 - Data challenge 1: OpenStreetMap

Map showing the roads in Tel Aviv - Yafo, Israel (focused because I used a larger land polygon and the coastline was messed up),  
The maps background and features are styled using the **Onix** color palette.  

<img src="5-OpenStreetMap(Onix).png" alt="5-OpenStreetMap(Onix)" width="60%"/>

## Map 6 - Red

Days 6,7,8 all show the same data, but in different color palettes,  
For this I took a similiar approach to how my wife makes these maps,  
but in pokemon colors, if you're looking for a good looking map of London,   
you can check out [her etsy shop](https://www.etsy.com/il-en/listing/1101325891/london-city-map-choose-your-color)

<a href="https://www.etsy.com/il-en/listing/1101325891/london-city-map-choose-your-color"><img src="https://i.etsystatic.com/32245569/r/il/c6a803/3408945690/il_794xN.3408945690_c082.jpg" alt="London Four Colors" width="25%"/></a>

Map showing the buildings, greenspaces, and railroads in London, England, United Kingdom.

The maps background and features are styled using the **Charmander** color palette. 

data from Open Zoomstack - OS data © Crown copyright and database right 2021

<img src="6-Red(Charmander).png" alt="6-Red(Charmander)" width="60%"/><img src="https://pokepalettes.com/images/sprites/poke/bw/4.png"/>

## Map 7 - Green

Days 6,7,8 all show the same data, but in different color palettes,  
For this I took a similiar approach to how my wife makes these maps,  
but in pokemon colors, if you're looking for a good looking map of London,   
you can check out [her etsy shop](https://www.etsy.com/il-en/listing/1101325891/london-city-map-choose-your-color)

The maps background and features are styled using the **Bulbasaur** color palette. 

data from Open Zoomstack - OS data © Crown copyright and database right 2021  

<img src="7-Green(Bulbasaur).png" alt="7-Green(Bulbasaur)" width="60%"/><img src="https://pokepalettes.com/images/sprites/poke/bw/1.png"/>

## Map 8 - Blue

Days 6,7,8 all show the same data, but in different color palettes,  
For this I took a similiar approach to how my wife makes these maps,  
but in pokemon colors, if you're looking for a good looking map of London,   
you can check out [her etsy shop](https://www.etsy.com/il-en/listing/1101325891/london-city-map-choose-your-color)

The maps background and features are styled using the **Squirtle** color palette. 

data from Open Zoomstack - OS data © Crown copyright and database right 2021  

<img src="8-Blue(Squirtle).png" alt="8-Blue(Squirtle)" width="60%"/><img src="https://pokepalettes.com/images/sprites/poke/bw/7.png"/>

## Map 9 - Monochrome

Map showing rivers and lakes in North America, all data form Natural Earth, rivers width by scale.  
The maps background and features are styled using the **Ditto** color palette.   

<img src="9-Monochrome(Ditto).png" alt="9-Monochrome(Ditto)" width="60%"/>

## Map 10 - Raster

A map created using a data elevation model (DEM) of Mars [freely available from NASA](https://astrogeology.usgs.gov/search/map/Mars/GlobalSurveyor/MOLA/Mars_MGS_MOLA_DEM_mosaic_global_463m) along with some digitized features around the Valles Marineris and Olympus Mons (the tallest mountain in the solar system).  
The map was styles with th **Gastly** color palette.  


<img src="10-Raster(Gastly).png" alt="10-Raster(Gastly)" width="60%"/>

## Map 11 - 3D

Map showing extruded buildings and roads in Tel Aviv - Yafo, Israel.   
extrusion is by z factor for roads, for buildings extrusion is by height when available, number of levels (times 4 meters),  
or 8 meters when neither height or levels is available.  
The maps background and features are styled using the **Porygon** color palette. 

<img src="11-3D(Porygon).png" alt="11-3D(Porygon).png" width="60%"/>

## Map 12 - Population

Map showing population change in Great Britain urban centers,  
Data is from the European Commission's Global Human Settlement Layer, Urban Centre Database 2015,  
displayed over the land layer from Open Zoomstack which is  OS data © Crown copyright and database right 2021   
No idea why Open Zoomstack doesn't iclude North Ireland.
The maps background and features are styled using the **Victreebel** color palette. 

<img src="12-Population(Victreebel).png" alt="12-Population(Victreebel)" width="60%"/>

## Map 13 - Data challenge 2: Natural Earth

Map displaying some of the Natural Earth available layers,  
layers shown are: Land, Bathymetry, Parks & Protected Areas, Urban Areas, RIver, Lakes, Airports and Sea Ports.  
Data is obviously from Natural Earth.
Since I used so many layers had to use more than one palette for this, so background and features are styled using the **Nidoqueen** and **Nidoking** color palettes.  

<img src="13-Natural Earth(Nidoqueen&Nidoking).png" alt="13-Natural Earth(Nidoqueen&Nidoking)" width="60%"/>

## Map 14 - Map with a new tool

Used <a href="https://studio.unfolded.ai">Unfolded Studio</a> to create this map,  
Just started it out and used a shared dataset which was called San Francisco elevation and seems to be divided into H# placekey hexagons.  
Changed the color scale to use **Venusaur** colors.  

<img src="14-New Tool(Venusaur).gif" alt="14-New Tool(Venusaur)" width="60%"/>

## Map 15 - Map made without using a computer

## Map 16 - Urban/rural

## Map 17 - Land

## Map 18 - Water

## Map 19 - Island(s)

## Map 20 - Movement

## Map 21 - Elevation

## Map 22 - Boundaries

## Map 23 - Data challenge 3: GHSL Global Human Settlement Layer

## Map 24 - Historical map

## Map 25 - Interactive map

## Map 26 - Choropleth map

## Map 27 - Heatmap

## Map 28 - The Earth is not flat

## Map 29 - NULL

## Day 30 - Metamapping day


### #30DayMapChallenge created by Topi Tjukanov

The official repository with the instructions and code of conduct available at [tjukanovt/30DayMapChallenge](https://github.com/tjukanovt/30DayMapChallenge).