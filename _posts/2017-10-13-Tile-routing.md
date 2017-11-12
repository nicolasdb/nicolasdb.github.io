---
title: "Tile routing"
categories:
  - Tuto
tags:
  - MDF
  - CNC
  - fusion360
---

## Objectif:
Certaines dales de platres sont à remplacer. C'est un modèle qu'on ne retrouvera pas facilement sur le marché.

{% raw %}<img src="https://user-images.githubusercontent.com/12049360/31553168-d2fb24b2-b039-11e7-825d-806273f62d7b.png
" alt="">{% endraw %}

Le job sera alors de modéliser la plaque en 3D et de reproduire la forme à la CNC.

## Production
### Fusion360

La modélisation est rapide, 30 min pour mesurer et reproduire en 3D.

{% raw %}<img src="https://user-images.githubusercontent.com/12049360/31553349-7f0fcc94-b03a-11e7-97a4-1cbe2d060ddc.png
" alt="">{% endraw %}

\+ achat de fraises spéciales pour gagner du tps.
+ Fraise droite à 2 coupes carbure 25mm  
[Numéro d'article: 902.250.11](http://www.garnotec.be/product/FR/133)  
28.31€ ttc
+ Fraise à rainurer en V. 90°    
[Numéro d'article: 915.127.11](http://www.garnotec.be/product/FR/347)  
27.59€ ttc



### steps to produce 10

- [x] precut @gedebois 10x 300x300x18mm MDF
- [x] Fix leftover MP 12mm
- [x] Do a profiling job "in" same size of the tile (300x300)
- [x] Add the tile, have to be tight
- [x] Fix other leftover and use a wedge to clamp the tile in place.
![image](https://user-images.githubusercontent.com/12049360/32214227-698569dc-be1e-11e7-9c00-c572978f1b18.png)

- [x] First pocketing job with 25mm tool bit,
- [x] Unclamp, new tile, pocketing, 10 times.
![image](https://user-images.githubusercontent.com/12049360/32214749-2c9dbb62-be20-11e7-9d08-3a107a44d226.png)

- [x] Cleaning profiling, 3mm straight tool, Also 10x
![image](https://user-images.githubusercontent.com/12049360/32214914-a4281b82-be20-11e7-97f5-8da2cb7d6ad8.png)
![image](https://user-images.githubusercontent.com/12049360/32214919-a94a84ce-be20-11e7-96ea-240a1d7b033a.png)

- [x] Last job, Chamfer, 90°, 3mm down
![image](https://user-images.githubusercontent.com/12049360/32214960-d5b75870-be20-11e7-8b2d-300beaa7b3d7.png)

- [x] Pack, take care to protect the edges, MDF is soft
![image](https://user-images.githubusercontent.com/12049360/32215022-ffe8755c-be20-11e7-963a-218fd7486cbc.png)

This job will be paint and place as replacement for broken tiles.

### Timings:
\- clamping setup, 30 min
\- pocketing, 8 min/pc
\- profiling, 2 min/pc
\- chamfer, 1 min/pc
\+ 3x 5 min in between to change tools, gcode and Z homing
