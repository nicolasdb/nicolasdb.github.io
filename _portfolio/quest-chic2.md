---
title: "CHIC2.0"
excerpt: "[Opencall] Cultural Hybridization In Common 2016-2017 - Un projet européen de mise en relation, de maillage, d’échange sur les processus créatifs autour de l’objet «tampon» et de la notion du «libre»."
header:
  image: /assets/images/portfolio/chicmain.jpg
  teaser: /assets/images/portfolio/chic-th.jpg
sidebar:
  - title: "Role"
    image: http://placehold.it/350x250
    image_alt: "logo"
    text: "Lead Fabmanger"
  - title: "Responsibilities"
    text: "Project management, hosting workshop, Opensource consultant and technical development"
gallery:
  - url: "https://user-images.githubusercontent.com/12049360/37783782-a066c11a-2df6-11e8-8bb3-bcdbaa9f4fb5.png"
    image_path: "https://user-images.githubusercontent.com/12049360/37783782-a066c11a-2df6-11e8-8bb3-bcdbaa9f4fb5.png"
    alt: "Math00"
  - url: "https://user-images.githubusercontent.com/12049360/37783837-b7915bc0-2df6-11e8-8c6d-b4bbf904049e.png"
    image_path: "https://user-images.githubusercontent.com/12049360/37783837-b7915bc0-2df6-11e8-8c6d-b4bbf904049e.png"
    alt: "3d validation"
  - url: "https://user-images.githubusercontent.com/12049360/37783956-08caf6cc-2df7-11e8-886b-fe5afe96cc57.png"
    image_path: "https://user-images.githubusercontent.com/12049360/37783956-08caf6cc-2df7-11e8-886b-fe5afe96cc57.png"
    alt: "prototypage"
---

#### Un projet européen de mise en relation, de maillage, d’échange sur les processus créatifs autour de l’objet «tampon» et de la notion du «libre».

### Openfab, un collectif de freelance, une guilde opensource

> A guild is an association of artisans or merchants who oversee the practice of their craft in a particular town. ([wikipedia](https://en.wikipedia.org/wiki/Guild))

Dans le cas d'Openfab, les membres partagent un intérêt pour la technologie, la motivation de faire ensemble et l'intérêt économique de mutualiser des ressources qui nous sont communes et nécessaires pour travailler ou développer nos savoir-faire.  

Le fablab s'est développé sur base de machines numériques dont les plans sont partagés sous licence libre.  
L'achat de kits réduit la barrière financière et leur assemblage active l'apprentissage des technologies associées. C'est à la fois moins cher, instructif et autonomisant.  
Enfin, leur mutualisation favorise une (bio)diversité d'usagers et d'usages qui, tel un terreau fertile, va activer le développement d'idées, de nouveaux projets et surtout, la mise en place de nouvelles méthodologies de travails en commun.

C'est donc naturellement, que le rôle d'Openfab dans le projet CHIC2.0, s'est focalisé sur **l'outil** et **l'usage**.

## Assister la fabrication d'un tampon
Qu'est-ce qu'un fablab peut proposer ?  
Par défaut, nous serons tentés de réaliser le tampon à l'aide des machines, par impression 3D ou encore par gravure au laser.  
Mais cela restreint cette production aux fablabs et nécessite des compétences relativement peu communes.

    ### Les contraintes de départ:
- l'outil doit aider la production des cachets
- l'outil peut être produit dans un fablab,
- son utilisation est facile pour “non-geek” et hors d'un fablab
- un outil low-tech, produit d'une recherche High-tech
- processus Opensource
- *bonus:*
   - utilisation sans ordi
   - utilisation sans électricité
- *extra challenge:*
**workshop en Italie == groupes d’enfants 8-12 ans**

## Les workshop à Bruxelles
Les 2 workshop proposés ont pour but d'agir en 2 temps, avec une période de maturation de l'idée entre les deux.
### L'outil

*Workshop technique, à Openfab -   
Développement et fabrication de machines*
- 1 machine légère pour le travail avec les enfants, super safe, mise à l'échelle de dessin. Guide + bic sur papier
- 1 machine moyenne pour la gravure dans des matériaux plus résistants en surface, linogravure, bois, caoutchouc, etc... Guide (On/off) + fraisage type dremel/proxxon.

Le choix s'est porté sur la technique du pantographe [dont le concept est exploré sur cette page](https://github.com/openfab-lab/chic2.0/blob/master/03BXL/2017-04-30-bxl1.md).

{% include gallery caption="This is a sample gallery to go along with this case study." %}

### L'usage
hackgate copyright Lucius Nieman CNN leaves it there right-sizing a giant stack of newspapers that you'll never read net neutrality algorithms RT algorithms TechCrunch 5% corruption, horse-race coverage Gardening & War section CTR try PR CPC David Cohn shoot a photo algorithms content is king Android Snarkmarket crowdfunding, Fuego Twitter topples dictators YouTube abundance WordPress Reuters try PR stupid commenters should isn't a business model bringing a tote bag to a knife fight.

![gification](https://i.pinimg.com/originals/2c/c3/5d/2cc35d828f31b0746fa7d4cdf86ed5fe.gif)

this is a work in Progress, loading ....

---
### Posts linked to this quest
<ul class="posts">
{% for post in site.tags.Chic limit: 20 %}  <!-- change the name after site.tags.***** to select the tag -->
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>
