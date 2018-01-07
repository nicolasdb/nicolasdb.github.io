---
title: "How to contribute"
layout: "archive"
header:
  image: "https://media.giphy.com/media/XnqQKPCUmaJWM/giphy.gif"
  # teaser: /assets/images/portfolio/badges01-th.jpg
permalink: /howto/
# date: 2016-02-24T03:02:20+00:00
---

![chair](https://media.giphy.com/media/XnqQKPCUmaJWM/giphy.gif)

### Ho, hi there.

First off, thank you for considering contributing to what I do. J'ai de temps en temps des propositions d'aide and yes, I need help. I don't know everything et je galère souvent sur des sujets qui dépassent mes compétences, mais continue de chercher par tâtonnements.   
But it's still difficult to me de trouver les moyens de définir, lister, i don't know... Déléguer est un art que j'apprend encore. De plus, je dois encore trouver le cadre pour ça et comment former certains.  

Ce site est un excercice et une exploration à ce sujet. I'm using github to host the website and it give me, and you, the ability to contribute (if you're willing to take the small time needed to learn how)

### Why do people contribute to open source? Plenty of reasons!

- Improve existing skills
- Meet people who are interested in similar things
- Find mentors and teach others
- Build public artifacts that help you grow a reputation (and a career)
- Learn people skills
- It’s empowering to be able to make changes, even small ones

*source: [why contributing?](https://opensource.guide/how-to-contribute/)*

# How can you contribute?

First, you can follow the guide to become an [Openfab superUser](https://github.com/openfab-lab/gamification-fablab/blob/master/Level-UP/guide-superuser.md).  
La partie github en tout cas.  
Ce qui permet déjà de [participer au travers des issues github](https://opensource.guide/how-to-contribute/#how-to-submit-a-contribution).  

Ensuite, there is this kind of framework i'm trying to put in place.   
Lors de la création d'une issue,
- tjs commencer par une part de contexte,
- proposer des objectifs et une ou plusieurs pistes pour les atteindres.
- et énoncer votre intérêt.  
ça peut être simplement que ça vous fait plaisir ou que vous avez envie d'apprendre une compétence ou peut-être que vous avez envie de travailler plus souvent dans le monde des fablabs et c'est une première expérience à gagner avant d'en tirer une rémunération. Ou vous voulez juste des euro ou encore du tps d'accès machine.

My point is that outside an amount of money, it is not easy to clearly define the value of help. *Well, money neither actually....*   
And sure, I'll be happy to receive it and I would like to know what make you happy to help me so we can grow trust on that, and maybe do more of what make us happy.

## What kinds of contributions I'm looking for.

Bien, cela peut-être n'importe quoi où vous vous sentez motivé d'aider, suivant vos propres forces.  
Here, I managed to list automatically posts on what I could need help. If you found something you're willing to learn, to help, to do, to... je ne sais pas, n'importe quel intérêt vous y voyez.  
My goal is to create as much opportunities as possible to barter a win/win deal situation with you.  

*for more : [What it means to contribute?](https://opensource.guide/how-to-contribute/#what-it-means-to-contribute)*

<ul class="posts">
{% for post in site.tags.contribute limit: 20 %}
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>
