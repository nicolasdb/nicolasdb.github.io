---
date: 2019/04/06
layout: page
#
# Content
#
subheadline: "Tutoriel FR"
title: "Honeycomb pattern"
teaser: "Comment créer un motif hexagonal à l'aide de Fusion360 en utilisant le Pattern Tool pour contrôler le nombre de répétitions et la distance entre les répétitions."
meta_description: "meta_description"
categories:
  - make
tags:
  - Fusion360
  - FR
#
# Styling
#
header: no
#  image_fullwidth: ""
#  image: ""
#  caption: ""
#  url: ""
image:
  title: ""
  thumb: "images/thumb/honeycomb-th.jpg"
  homepage: "images/pranav-kumar-jain-PR_0IPlMXgk-unsplash.jpg"
  caption: "Photo by Pranav Kumar Jain onUnsplash"
  url: "https://unsplash.com/@peejayvisual?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText"
#  
# Metainformation & Customization
#
breadcrumb: true
---


> J'aime bien utiliser des motifs dans mes projets. 

Dernièrement, j'ai voulu faire la gravure d'un motif hexagonale au laser. De base, c'est très simple : je commence par un hexagone, que je duplique et déplace un peu. Je groupe, et duplique une nouvelle fois, je groupe, déplace, je groupe, etc. Copier/coller des groupes permet évidemment d'aller plus vite.

D’habitude j'utilise Inkscape et ses outils de magnétisme afin d'accrocher à des références et garder un alignement constant dans mon copypasta. 

Sauf que. Gniiiiii ! Mon motif n'est pas droit !

Bien sûr, c'est une fois presque fini que je me rends compte que des petites erreurs se sont glissées et se sont répétées et accumulées à chaque copie.

# Comment générer un motif hexagonale dans Fusion360?

![https://user-images.githubusercontent.com/12049360/55670413-1bfcf200-5884-11e9-84a0-1716f0b01eea.png](https://user-images.githubusercontent.com/12049360/55670413-1bfcf200-5884-11e9-84a0-1716f0b01eea.png)

## 1. Comprendre le motif

Pour créer un motif en forme de nid d'abeilles, c'est très simple. Il vous suffit de partir d'un cercle, de centrer un hexagone et de suivre les étapes de construction d'une fleur de vie.

**La fleur de vie:**

![https://user-images.githubusercontent.com/12049360/55671077-418df980-588c-11e9-83bb-9caeed096286.png](https://user-images.githubusercontent.com/12049360/55671077-418df980-588c-11e9-83bb-9caeed096286.png)

**Et le résultat avec les hexagones**

![https://user-images.githubusercontent.com/12049360/55669291-dafde100-5875-11e9-9bfb-857755110f6a.png](https://user-images.githubusercontent.com/12049360/55669291-dafde100-5875-11e9-9bfb-857755110f6a.png)

Nous sommes encore dépendants de copier-coller multiples, plus ou moins faciles selon le logiciel de dessin utilisé. De plus, si pour des raisons X, je souhaite modifier ou adapter la taille des cellules ou l'espace entre elles, je dois recommencer.

<aside>
💡 Dans Rhino, le Array Tool permet de répéter des objets selon des points de référence. Inkscape utilise le Tile Tool et Fusion360 le Pattern Tool. Ces outils permettent d'adapter des formes à des références et de contrôler le nombre de répétitions et la distance entre les répétitions.
</aside>
<br>
Aujourd'hui, j'essaie de créer mon motif à l'aide de Fusion360, mais la méthode est la même peu importe le logiciel utilisé.

## 2. Quelles sont les dimensions qui nous intéressent?

La largeur de cellule (hexaX) est de 10 mm et l'écart (space) est de 3 mm, ce qui donne un diamètre de 26 mm pour le cercle.

![https://user-images.githubusercontent.com/12049360/55669295-e3561c00-5875-11e9-87ea-de5dbeaf0ffc.png](https://user-images.githubusercontent.com/12049360/55669295-e3561c00-5875-11e9-87ea-de5dbeaf0ffc.png)

Ensuite, le nombre de cellules en X et Y.
Soit **Xcount** et **Ycount**.

## 3. Définir la maille de base

Un motif rectangulaire dans Fusion360 ne permet qu'un maillage rectangulaire, c'est-à-dire une répétition de n1 dans un axe X et n2 dans l'axe perpendiculaire Y. Pour cette raison, j'ai préparé mon motif de base avec 2 cellules disposées en diagonale.

![https://user-images.githubusercontent.com/12049360/55670036-721b6680-587f-11e9-8558-c27402a68934.png](https://user-images.githubusercontent.com/12049360/55670036-721b6680-587f-11e9-8558-c27402a68934.png)

Ensuite, il faut déterminer les deux valeurs de décalage du motif.

1. Sur l'axe X, c'est simplement le rayon du cercle. **R=13mm** (voir plus haut)
2. Sur Y, ça se corse et j'ai dû retourner en classe de trigonométrie pour formuler le décalage précis.
    
    ![https://user-images.githubusercontent.com/12049360/55669965-16041280-587e-11e9-8789-4072d41c9f1f.png](https://user-images.githubusercontent.com/12049360/55669965-16041280-587e-11e9-8789-4072d41c9f1f.png)
    

Ce qui nous donne `sin60° * R` **= 11.26mm**, valeur que je double pour décaler de 2 cellules.

## R-pattern

*note: il est plus facile d'exécuter la fonction après extrusion du motif de base.*

Voici ci-dessous, la fonction "R-pattern" 3x3 avec

`R` sur l'axe-X et `(sin60 * R)*2` sur l'axe-Y

![https://user-images.githubusercontent.com/12049360/55670131-e1458a80-5880-11e9-9049-316bac03ba5d.png](https://user-images.githubusercontent.com/12049360/55670131-e1458a80-5880-11e9-9049-316bac03ba5d.png)

## 4. Ready to export dxf

Pour préparer le fichier 2D à utiliser pour la découpe laser :

1. Je crée un objet (plaque) à partir duquel je soustrais mon motif.
2. J'ajoute un nouveau "sketch" et je projette l'objet. [Voir ceci](https://youtu.be/PuI2iWmngtM?t=87)
3. J'exporte le "sketch" en .DXF

Ensuite, j'importe ce .dxf dans Inkscape pour finaliser l'intégration dans mon design.

![https://user-images.githubusercontent.com/12049360/55671627-608f8a00-5892-11e9-962c-eae4e7e65d73.png](https://user-images.githubusercontent.com/12049360/55671627-608f8a00-5892-11e9-962c-eae4e7e65d73.png)

[Voici le fichier Fusion360](https://a360.co/2UBzilG)