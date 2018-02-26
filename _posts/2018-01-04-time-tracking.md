---
date: 2018/01/04
title: "Making a timetracker device"
excerpt: "I need a time tracker to makes my time management easier than ever"
header:
  # image:
  teaser: "/assets/images/post/timey-th.jpg"
  # og_image:
categories:
  - Post
tags:
  - backoffice
  - Openfab
  - timelord
  - Openbadge
  - Gamification
  - contribute
  - FR
---

![image](https://user-images.githubusercontent.com/12049360/34566976-d724690a-f160-11e7-95a8-524f1e7ea4f6.png)
 *source: [3D printed ZEI time tracker makes time management easier than ever](http://www.3ders.org/articles/20161026-3d-printed-zei-time-tracker-makes-time-management-easier-than-ever.html)*

### Contexte
J'essaye de gagner mes points de TimeLord et même si je le fait de mieux en mieux, ça reste par période et je zap dès qu'il y a une période de stress/rush. J'aimerais m'améliorer.
Comme d'habitude, prendre une nouvelle habitude, ce n'est pas facile et c'est plein de petites embûches qui sont très efficaces pour ne pas que t'y arrive. ddjeu.

## Objectif(s)
J'avais trouvé ceci:
![image](https://user-images.githubusercontent.com/12049360/34565173-0b05db8e-f15a-11e7-8a00-1c680d93bb4f.png)
*source: [ZEIº helps you achieve more in less time.](https://timeular.com/)*

Mais c'est quand même bcp plus cher (116€) et sans version DIY comme ils le proposaient sur le kickstarter, et ça vient avec un logiciel dont une version pro est en supplément... mouais.  
Du coup....   

**Comment fabriquer quelque chose, simple d'utilisation, qui éviterai de passer par des clics superflus via l'application ou l'extension et qui visuellement rappelle de faire cette action?**

Je me dis que ce brol, c'est pas bien compliqué quand même. Un arduino, du bluetooth, un gyroscope et le tour est joué.    
Genre [tinyTILE (intel)](https://www.sparkfun.com/products/14281) qui embarque tout en un, ou [le photon (particule)](https://www.sparkfun.com/products/13764)  
J'ai trouvé un tuto sur ce controleur et c'est même moins cher (19$ au lieu de 39$).

## Propositions
- **difficulté 1: gyroscope + arduino + action Toggl via code**

Le tuto ne parle pas de gyroscope comme déclencheur mais d'une action via un bouton.  
[Useful Toggl Time Tracker with Particle and Node](https://www.sitepoint.com/how-to-make-a-useful-toggl-time-tracker-with-particle-and-node/)   
Ben ouais, plus simple un bouton :)
- **difficulté 2: boutons + particule photon + action Toggl via nodeJS**

Mais bon, faire une planche test avec des boutons, ça va encore prendre du tps et si j'arrive à lier un bouton, est-ce que j'arriverai pas à déjà lier un bouton "fonction" du clavier?   

- **difficulté 3: keyboard F-key + action Toggl via API?**

J'imagine qu'en vue du code précédent, y a peut-être une astuce à faire en passant par "processing" en liant une touche clavier à la place du "photon" + bouton.
[keyReleased](https://processing.org/reference/keyReleased_.html)  

Y a plus qu'à apprendre comment fonction **nodeJS**


*note: this post is linked to [this issue](https://github.com/nicolasdb/nicolasdb.github.io/issues/21), feel at ease to contribute.*
