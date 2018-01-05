---
title: "It's time to pimp my Anet E10"
date: 2018/01/05
categories:
  - Post
tags:
  - Openfab
  - 3dPrint
---

![image](https://user-images.githubusercontent.com/12049360/34579101-e513405a-f187-11e7-8cd5-0796ed44a43e.png)

### Contexte
J'ai pu commander quelques machines en kit dernièrement. Le deal est de financer l'achat de 4 kits, en revendre 3 et financer ainsi une machine pour le lab. Mais bien que les machines sont pas mal du tout et que l'ensemble est rigide et imprime bien.

Les problèmes à l'origine sont :
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
- Ajouter des petits guides pour les ressorts du bed
- rotation des moteurs Z
- raccourcir le tube PTFE
- bourriner avec une vis à bois le réglage du chariot X
- ventilo https://www.thingiverse.com/thing:2481362
- Z limit https://www.thingiverse.com/thing:2482030
- support PSU https://www.thingiverse.com/thing:2467824
- some foots to make place for electronics under. https://www.thingiverse.com/thing:2659913
- 2 filtres pour filament https://www.thingiverse.com/thing:1692395
- un boitier pour le fuse switch C14 https://www.thingiverse.com/thing:2119103
- un tendeur pour la courroie X https://www.thingiverse.com/thing:2589638



## Steps
#### **Roulements Y IGUS**

J'ai demandé des échantillons chez Igus, j'avais envie de tester les [paliers polymère Drylin](https://www.igus.com/wpck/17748/Motek14_N14_6_3_Vollkunststofflager) en remplacement des roulements linéraire classique (LM8UU ball bearings).

à voir: https://youtu.be/ZGBipbgwgME

- **difficulté 2: boutons + particule photon + action Toggl via nodeJS**

Mais bon, faire une planche test avec des boutons, ça va encore prendre du tps et si j'arrive à lier un bouton, est-ce que j'arriverai pas à déjà lier un bouton "fonction" du clavier?   

- **difficulté 3: keyboard F-key + action Toggl via API?**

J'imagine qu'en vue du code précédent, y a peut-être une astuce à faire en passant par "processing" en liant une touche clavier à la place du "photon" + bouton.
https://processing.org/reference/keyReleased_.html  

Y a plus qu'à apprendre comment fonction **nodeJS**
