---
date: 2018/01/05
title: "Time to pimp my Anet E10"
excerpt: "I bought this last 3D printer and it's time to pimp this mtfucka"
header:
  # image:
  teaser: "/assets/images/post/AnetE10.1-th.jpg"
  # og_image:
categories:
  - Post
tags:
  - Openfab
  - 3dPrint
---
*note: this post is linked to [this issue](https://github.com/nicolasdb/nicolasdb.github.io/issues/16), feel at ease to contribute.*



J'ai pu commander quelques machines en kit dernièrement.

![image](https://user-images.githubusercontent.com/12049360/34579101-e513405a-f187-11e7-8cd5-0796ed44a43e.png)

### Contexte
Le deal est de financer l'achat de 4 kits, en revendre 3 et financer ainsi une machine pour le lab. Mais bien que les machines sont pas mal du tout et que l'ensemble est rigide et imprime bien, j'y trouve plusieurs problèmes.

A l'origine je trouve que :
- le transport merdique (comme d'hab, un effort est fait par les services postaux concernant la délicatesse de leur livreur)
- matos chinois et faiblesse du pack et des finitions
  - alim DOA (dead on arrival)
  - courroies défaites
  - coup et griffe sur le bed à cause des vibrations/chocs
  - le support de lit est torché donc compensation avec les vis
  - le chariot X est faible, 3 points seulement de contact, difficile à régler et donc jeu et imprécisions
  - moteurs Z mal orienté, nécessite une rotation de 90° pour déplacer le connecteur.
  - difficulté à régler précisément les endstops pour Z et X

Bref, moultes optimisations possibles :D

**note:** Pour moi, c'est justement l'intérêt d'une telle machine. C'est chinois, c'est en kit et c'est pas cher. La machine imprime très bien, toutes fois, il est certain que les composants sont terminés au pipi (ça ne fera donc pas long feu) et qu'il y a une large marge de manoeuvre pour de l'upgrade. Ce qui est en soi, pour moi, le plus amusant. #mecano4ever :D

## Objectif(s)
à commencer par
- remplacer les roulements Y par des IGUS
- Ajouter des petits guides pour les ressorts du bed [Spring cups](https://www.thingiverse.com/thing:2044042)
- rotation des moteurs Z
- raccourcir le tube PTFE
- bourriner avec une vis à bois le réglage du chariot X
- [ventilo](https://www.thingiverse.com/thing:2481362)
- [Z limit](https://www.thingiverse.com/thing:2482030)
- [support PSU](https://www.thingiverse.com/thing:2467824)
- [some foots to make place for electronics under](https://www.thingiverse.com/thing:2659913)
- [2 filtres pour filament](https://www.thingiverse.com/thing:1692395)
- un boitier pour le [fuse switch C14](https://www.thingiverse.com/thing:2119103)
- [un tendeur pour la courroie X](https://www.thingiverse.com/thing:2589638)



## Steps
### Roulements Y IGUS

J'ai demandé des échantillons chez Igus, j'avais envie de tester les [paliers polymère **igus drylin RJ4JP**](https://www.igus.com/wpck/17748/Motek14_N14_6_3_Vollkunststofflager) en remplacement des roulements linéraire classique (LM8UU ball bearings).

![img](https://cdn.thingiverse.com/renders/f2/80/a4/3a/d2/895dfd9d3ce728b0b494b4255fc85dda_preview_featured.jpg)

à voir: [**Should you be using IGUS polymer bushings?** *by Thomas Sanladerer*
](https://youtu.be/ZGBipbgwgME)

### spring cups

Pour contraindre les ressorts du lit. Ils se déforment et c'est pas très stable. Avec c'est mieux. :)   
[spring guide](https://www.thingiverse.com/thing:2171918)

![image.png](https://images.zenhubusercontent.com/599be89f8f62dc7798c39c2f/65373525-1994-4bef-97be-ccc8b6f720b0)

### 90° motors Z

Petit 1/4 de tour pour ne plus que le cable ne soit dans le chemin du lit.
![image.png](https://images.zenhubusercontent.com/599be89f8f62dc7798c39c2f/018ae3fb-5cf3-4cf2-be6f-f2f4647ab3d9)
### PTFE tube

Julien D. m'a conseillé de réduire la longueur au maximum pour réduire les frottements.

![image.png](https://images.zenhubusercontent.com/599be89f8f62dc7798c39c2f/14876a98-ae8f-4598-b055-df3428e38032)
### X cart v0

Les roues du X cart sont très difficile à régler, du jeu reste et c'est pas facile à corriger.  
Une bonne vis pour forcer la zone de réglage et on en parle plus.

![image.png](https://images.zenhubusercontent.com/599be89f8f62dc7798c39c2f/96981e6c-c99f-41dd-a7f1-a6a23b7f0867)

### better extruder fan holder
Le boitier d'origine et le ventilo refroidit bcp trop fort, à la fois le radiateur (bien) à la fois la tête d'extrusion (mal)   
[Ce fan holder gère mieux le flux d'air](https://www.thingiverse.com/thing:2481362)

![image.png](https://images.zenhubusercontent.com/599be89f8f62dc7798c39c2f/63547cf4-8831-4f4e-86a9-ec8a1664f24b)

And more to come:
- [Z limit](https://www.thingiverse.com/thing:2482030)
- [support PSU](https://www.thingiverse.com/thing:2467824)
- [some foots to make place for electronics under](https://www.thingiverse.com/thing:2659913)
- [2 filtres pour filament](https://www.thingiverse.com/thing:1692395)
- un boitier pour le [fuse switch C14](https://www.thingiverse.com/thing:2119103)
- [un tendeur pour la courroie X](https://www.thingiverse.com/thing:2589638)



*note: this post is linked to [this issue](https://github.com/nicolasdb/nicolasdb.github.io/issues/16), feel at ease to contribute.*
