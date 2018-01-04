---
title: "Making a timetracker device"
date: 2018/01/04
categories:
  - Post
tags:
  - backoffice
  - Openfab
  - timelord
  - openbadge
---

![image](https://user-images.githubusercontent.com/12049360/34566976-d724690a-f160-11e7-95a8-524f1e7ea4f6.png)
 *source: [3D printed ZEI time tracker makes time management easier than ever](http://www.3ders.org/articles/20161026-3d-printed-zei-time-tracker-makes-time-management-easier-than-ever.html)*

#### contexte
J'essaye de gagner mes points de TimeLord et même si je le fait de mieux en mieux, ça reste par période et je zap dès qu'il y a une période de stress/rush. J'aimerais m'améliorer.
Comme d'habitude, prendre une nouvelle habitude, ce n'est pas facile et c'est plein de petites embûches qui sont très efficaces pour ne pas que t'y arrive. ddjeu.
## objectif
J'avais trouvé ceci:
![image](https://user-images.githubusercontent.com/12049360/34565173-0b05db8e-f15a-11e7-8a00-1c680d93bb4f.png)
https://timeular.com/

Mais c'est quand même bcp plus cher (116€) et sans version DIY comme ils le proposaient sur le kickstarter, et ça vient avec un logiciel dont une version pro est en supplément... mouais.  
Du coup....

Je me dis que ce brol, c'est pas bien compliqué quand même. Un arduino, du bluetooth, un gyroscope et le tour est joué.    
Genre [tinyTILE (intel)](https://www.sparkfun.com/products/14281) qui embarque tout en un, ou [le photon (particule)](https://www.sparkfun.com/products/13764)  
J'ai trouvé un tuto sur ce controleur et c'est même moins cher (19$ au lieu de 39$).

Le tuto ne parle pas de gyroscope mais d'une action via un bouton.  
https://www.sitepoint.com/how-to-make-a-useful-toggl-time-tracker-with-particle-and-node/
