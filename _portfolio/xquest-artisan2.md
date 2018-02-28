---
title: "Artisan2.0"
excerpt: "[Opencall] du Contrat de Quartier Maelbeek, Ixelles, Bruxelles"
header:
  image: /assets/images/portfolio/artisan2.0.jpg
  teaser: /assets/images/portfolio/artisan2.0-th.jpg
sidebar:
  - title: "Role"
    # image: http://placehold.it/350x250
    # image_alt: "logo"
    text: "Project manager"
  - title: "Responsabilités"
    text: "Mentor, support et lien avec la commune"
---

Dans le cadre du contrat de quartier Maelbeek, une série de workshops sur le thème « artisan 2.0 » sont proposés. Les workshops sont mis en place par l’OpenFab, écosystème 100% indépendant qui mutualise les capacités de chacun pour être catalyseur d’innovation et de créativité. L’autogestion, le croisement des disciplines et la recherche par expérimentation sont essentiels dans ce FabLab.   
Les workshops seront encadrés par Nicolas de Barquin, FabLab manager, Dewi Brunet, artiste plieur.  
Un grand merci pour leur aide à Paul Le Coz, Anne-Sophie Muller, Sarah Ledjou et Désiré Nwaobasi.

Artisan 2.0 vise à partager des passions et des savoir-faire manuels en mettant à disposition les opportunités offertes par les outils numériques.

Le pliage sera le fil conducteur de cette série de workshops.   
La pratique du pliage (notamment l’origami) permet de créer des volumes-surfaces repliables aux potentiels incroyables : bijoux, nœud papillon, capuche repliable, robe, costume, parapluie, lampe, cloison, paroi insonorisée, abri portable, décors…

![dsc03567](https://user-images.githubusercontent.com/25649502/30801240-f11c9080-a1e2-11e7-9430-613e42f5c9fe.JPG)

>Le pliage nécessite une extrême précision et rigueur. Heureusement, les outils numériques disponibles aujourd’hui sont d’une grande aide pour faciliter la pratique et aller plus loin dans les applications. La découpe-laser est un outil simple à manipuler qui permet de découper, graver, préparer des formes avec une précision parfaite. Idéale pour créer des « moules à prépliage » pour origamis ou des « métiers à plisser » pour plier du textile. La robotique avec Arduino permettrait de créer des origamis réagissant à différents stimuli pour s’allumer, se replier, prendre vie.  
> \- Dewi Brunet -

## 10 jours de workshop en 2017
Nos objectifs étaient clairs.  
- faire découvrir cette intersection entre artisanat, traditionnel au sens du terme, et les technologies de la fabrication numérique.
- mettre l'accent sur les habitants du quartier.
- 2 évènements en début et fin de projet.
- 10 jours de stages ou workshops, en bloc ou répartis sur la période du projet.

On aurait pu se contenter de faire comme ça, mais je voulais faire autrement parce que faire des stages pour faire des stages, ne faisait pas de sens pour moi. Et de plus, pourquoi ne pas interconnecter ce projet avec d'autres opportunités.

![dsc03567](https://github.com/openfab-lab/artisan2.0/blob/master/Photo/W03%20J2..JPG?raw=true)


Nous avons commencé durant l'été, et le projet s'est déroulé en plusieurs étapes itératives.  
1. Dewi et Anne-Sophie ont travaillé ensemble pour explorer le pliage associé aux textiles.
2. Le résultat de cette coopération a été exposée lors du "Design September" qui organisait une expo visant à mettre en valeur les créations de fablab Bruxellois.
3. Nous avons réalisé une série de "teaser" de workshop lors des portes-ouvertes. Mini atelier de 20min pour tester et montrer le travail de Dewi et Anne-Sophie.  
L'objectif était de tester la technique avec du public et en faire ressortir une thématique plus directrice, tout en bénéficiant de la com "Design September" + la journée sans voiture.
4. La thématique affinée, nous avons initié l'itération au travers de workshop d'une journée. Où les participants découvraient et alimentaient la réflexion tout en apprenant avec Dewi.  
Nous avons répété ceux-ci à 6 reprises. Chaque workshop étant amélioré et la thématique affinée.  
5. Un grand workshop de 4 jours, inspiré des "hackathon" clôturait cette série de 10 jours.  
4 jours pour aller jusqu'au bout d'un projet, d'une idée.  

## Résultat
Un lampion luminescent aux Leds simple et sa version 2.0, avec son Arduino embarqué, ses panneaux solaires, sa batterie, ses leds et ses moteurs.  
Toute cette électronique pour rendre autonome en énergie la lampe, mais aussi lui donner vie.  
En journée, la lampe s'ouvre et découvre les panneaux solaires qui charge le système en énergie.  
Lorsque la nuit tombe, elle se referme, reprend sa forme de boule et enfin, allume les leds.

---
### Posts linked to this quest
<ul class="posts">
{% for post in site.tags.Artisan2 limit: 20 %}  <!-- change the name after site.tags.***** to select the tag -->
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>
