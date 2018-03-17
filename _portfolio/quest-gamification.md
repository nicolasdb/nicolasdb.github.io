---
title: "Gamification"
excerpt: "[Mod] Set rules and techniques who are intended to leverage people's natural desires for socializing, learning, mastery skills"
header:
  image: /assets/images/portfolio/gami.jpg
  teaser: /assets/images/portfolio/gami-th.jpg
sidebar:
  - title: "Quest"
    image: http://cdn.3plearning.com/wp-content/blogs.dir/7/files/2017/03/Shutterstock-gamification-banner-4-of-4.png
    image_alt: "me"
    text: "work hard, play hard"
  - title: "Skills"
    text: "OH yeah"
gallery:
  - url: https://geekandsundry.com/wp-content/uploads/2017/07/Scott-Pilgrim-FI.png
    image_path: https://geekandsundry.com/wp-content/uploads/2017/07/Scott-Pilgrim-FI.png
    alt: "placeholder image 1"
  - url: https://vignette4.wikia.nocookie.net/powerlisting/images/a/a1/Scott_Pilgrim_Power_Of_Love_Sword.png/revision/latest?cb=20130424223549
    image_path: https://vignette4.wikia.nocookie.net/powerlisting/images/a/a1/Scott_Pilgrim_Power_Of_Love_Sword.png/revision/latest?cb=20130424223549
    alt: "placeholder image 2"
  - url: https://cdn.vox-cdn.com/thumbor/kbf050Pltzzpuoc9DUAOSOAMzXw=/0x0:1920x1080/1200x800/filters:focal(807x387:1113x693)/cdn.vox-cdn.com/uploads/chorus_image/image/54383593/a70ab82c-6119-4ea5-988b-9aa24e716d9f.0.0.jpg
    image_path: https://cdn.vox-cdn.com/thumbor/kbf050Pltzzpuoc9DUAOSOAMzXw=/0x0:1920x1080/1200x800/filters:focal(807x387:1113x693)/cdn.vox-cdn.com/uploads/chorus_image/image/54383593/a70ab82c-6119-4ea5-988b-9aa24e716d9f.0.0.jpg
    alt: "placeholder image 3"
---
### Context

2016, I was browsing the TED talk web site and then, I discover this:  

{% include video id="dE1DuBesGYM" provider="youtube" %}
*Games like World of Warcraft give players the means to save worlds, and incentive to learn the habits of heroes. What if we could harness this gamer power to solve real-world problems? Jane McGonigal says we can, and explains how.*

And yeah, indeed, I was, kind of, frustrated by all these litle games as "pokemon GO", "sudoku", "candycrush" and shit.  
Why is it so difficult to attract people in a fablab, a fun place where the time you spent is to build something and yourself.

## What exploration?

As I stand out here in the wonders of the unknown at Hadley, I sort of realize there’s a fundamental truth to our nature, Man must explore . . . and this is exploration at its greatest.
We are all connected; To each other, biologically. To the earth, chemically. To the rest of the universe atomically.

{% include gallery caption="This is a sample gallery to go along with this case study." %}

Houston, Tranquillity Base here. The Eagle has landed.
As we got further and further away, it [the Earth] diminished in size. Finally it shrank to the size of a marble, the most beautiful you can imagine. That beautiful, warm, living object looked so fragile, so delicate, that if you touched it with a finger it would crumble and fall apart. Seeing this has to change a man.



![gification](https://i.pinimg.com/originals/fe/24/dc/fe24dc2b3440d3622249452d391f4393.gif)

this is a work in Progress, loading ....

---
### Posts linked to this quest
<ul class="posts">
{% for post in site.tags.Gamification limit: 20 %}  <!-- change the name after site.tags.***** to select the tag -->
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>
