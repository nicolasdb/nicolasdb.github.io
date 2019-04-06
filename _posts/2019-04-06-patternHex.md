---
date: 2019/04/06
title: "Honeycomb pattern"
excerpt: "Comment générer un motif hexagonale avec Fusion360"
header:
  image: "/assets/images/post/moucharabieh.jpg"
  teaser: "/assets/images/post/honeycomb-th.jpg"
  og_image: "/assets/images/post/hexagonSize.png"
categories:
  - Post
tags:
  - Inkscape
  - Fusion360
  - FR
---

*note: this post is linked to [this issue](https://github.com/nicolasdb/nicolasdb.github.io/issues/113), feel welcome to contribute.*

J'aime bien utiliser des motifs dans mes projets.  
Dernièrement, j'ai voulu faire la gravure d'un motif hexagonale au laser.  
De base, c'est très simple. Je commence par un hexagone, que je duplique et déplace un peu. Je groupe, et duplique une nouvelle fois, je groupe, déplace, je groupe, etc...  
Copier/coller des groupes, permet évidemment d'aller plus vite.  

J'utilise inkscape et ses outils de magnétisme afin d'accrocher à des références et garder un alignement constant dans mon copypasta.  

Mais, bien sûr, une fois presque fini, je me rends compte que des petites erreurs se sont glissées et se sont reportées et se sont accumulées à chaque copie.  
Gniiiiiiiiiiiii, mon motif est pas droit!  

# Générer un motif hexagonale dans Fusion360

![image](https://user-images.githubusercontent.com/12049360/55670413-1bfcf200-5884-11e9-84a0-1716f0b01eea.png)


## Comprendre le motif
Pour dessiner un motif en nid d'abeilles, c'est assez simple. Il suffit de partir d'un cercle, puis y centrer un hexagone et suivre les étapes de construction d'une fleur de vie.

**La fleur de vie**  
![image](https://user-images.githubusercontent.com/12049360/55671077-418df980-588c-11e9-83bb-9caeed096286.png)

**Et le résultat avec les hexagones**  
![image](https://user-images.githubusercontent.com/12049360/55669291-dafde100-5875-11e9-9bfb-857755110f6a.png)

Mais on dépend encore de copypasta multiple, plus ou moins facilité selon le logiciel de dessin utilisé.  
De plus, si pour X raisons, je veux modifier ou adapter les tailles de cellules ou l'écart entre elles. Je dois recommencer.  

## Les fonctions Array (rhino), Tile (inkscape) ou Pattern (Fusion360)
Dans ce cas, je cherche à créer mon motif à partir de Fusion360, mais la logique est identique quel que soit le logiciel.  

### Quelles sont les dimensions qui nous intéressent?
Je veux pouvoir controler mon motif selon la taille de l'hexagone et de l'écart entre 2 cellules.  
Soit **hexaX=10mm**, la largeur de cellule et **space=3mm**, l'écart.  
Ce qui nous donne un diamètre de 26mm pour notre cercle.  
![image](https://user-images.githubusercontent.com/12049360/55669295-e3561c00-5875-11e9-87ea-de5dbeaf0ffc.png)

Ensuite, le nombre de cellules en X et Y.  
Soit **Xcount** et **Ycount**.  

### Le motif de base
Un "rectangular pattern" dans Fusion360, ne permet qu'un maillage rectangulaire, c'est-à-dire une répétition de n1 dans un axe **X** et n2 dans l'axe perpendiculaire **Y**.  
J'ai donc préparé mon motif de base avec 2 cellules dans leur diagonale.  

![image](https://user-images.githubusercontent.com/12049360/55670036-721b6680-587f-11e9-8558-c27402a68934.png)

Ensuite, il faut déterminer les 2 valeurs de décalage du motif.  
1. Sur l'axe X, c'est simplement le rayon du cercle. **R=13mm**
2. Sur Y, ça se corse et j'ai dû retourner en classe de trigonométrie.  
![image](https://user-images.githubusercontent.com/12049360/55669965-16041280-587e-11e9-8789-4072d41c9f1f.png)  

Ce qui nous donne `sin60 * R = 11.26`, valeur que l'on double pour décaler de 2 cellules vers le haut.  

## R-pattern
Après extrusion du motif de base, il est plus facile d'exécuter la fonction sur ceux-ci.  

Ci-dessous, la fonction "R-pattern" 3x3 avec `R` sur l'axe-X et `(sin60 * R)*2` sur l'axe-Y  
![image](https://user-images.githubusercontent.com/12049360/55670131-e1458a80-5880-11e9-9049-316bac03ba5d.png)

## Ready to export dxf
Pour faciliter l'export d'un fichier 2D utilisable pour la découpe laser.
1. Je créé un objet (plaque) duquel je soustrais mon motif.  
2. Nouveau "sketch" et projection de l'objet. [(voir ceci)](https://youtu.be/PuI2iWmngtM?t=87)
3. Export du "sketch" en .DXF

J'importe ensuite ce .dxf dans Inkscape pour finaliser l'incorporation dans mon design.  

![image](https://user-images.githubusercontent.com/12049360/55671627-608f8a00-5892-11e9-962c-eae4e7e65d73.png)

Voici le fichier Fusion360 https://a360.co/2UBzilG
