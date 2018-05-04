---
title: "A maker abroad"
excerpt: "[Dev] The further we go, the further we are close to everything. Geee, that's deep, man"
header:
  image: /assets/images/portfolio/trip1.1.jpg
  teaser: /assets/images/portfolio/trip1.1-th.jpg
sidebar:
  - title: "Role"
    image: "/assets/images/portfolio/trip-rl.jpg"
    text: "Going abroad"
  - title: "Responsibilities"
    text: "Fabmanager, explorer and scribe"
---

### Hi There,
My Friends started a money pool to collect funds for helping me fulfil a new project, which is in continuity of [Openfab](openfab.be) and will explore new boundaries within the [Vulca's network](https://vulca.eu/about-us/).  

>Nous organisons une levée de fonds pour aider Nicolas à accomplir son nouveau projet. Après avoir offert 7 ans à OpenFab, il a envie d’approfondir les sujets qui lui tiennent à cœur en explorant les différents lieux de création en Europe (et plus loin).
Pour réaliser ce projet, il a besoin d’argent. Vous le connaissez, il est trop humble pour demander, donc on demande pour lui. :)

 _Yes, how awesome they are, right? I'm lucky, I terribly know_

## A maker abroad

>On ne connaît pas encore son itinéraire précis, mais on sait que tout ce qu’il va découvrir, il nous le retranscrira via internet ou au cours d’une discussion passionnée et passionnante. Les thèmes tourneront autour de la gamification et de la transmission de savoir-faire.
Faites passer ce message à tous ceux et celles qui ont un jour croisé la route de Nicolas. Et faites un don cette page.
Merci d’avance !

>Odile, Brice, Anne-Camille

So the goal is going abroad in Europe, ~~be wasted all the time, doing drugs and shit~~ _mais noooon, chuch there!_       
To do so, I'll met with local fablabs, makers and peoples around them, creating bridges and explore different kind of opportunities.   
I'll explore gamification, and shit..... ... >to continue>
I already came back with new ideas, new solutions for Openfab when going in Denmark, France or Spain. And I want to do more.  

For that, I'll continue to learn how to master github, the old, long and (for most) difficult art of documenting. I'll mark out the route in a journal, [my portfolio](nicolasdb.github.io), so the next will not have to start from scratch.  

The main challenges to overcome, is:
- money for travelling, accommodations and to eat,
- the method of documenting and publishing,
- how to enable opportunities?
- where to go next?



*note: you can participate on this page by using [issues on my github](https://github.com/nicolasdb/nicolasdb.github.io/issues/), feel at ease to contribute.*

---
### Posts linked to this quest
<ul class="posts">
{% for post in site.tags.Trip limit: 20 %}  <!-- change the name after site.tags.***** to select the tag -->
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>
