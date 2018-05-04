---
title: "A maker abroad"
excerpt: "[Mod] A passport for maker communities, to earn skills and share trust, to explore and meet makers without borders "
header:
  image: /assets/images/portfolio/passport.jpg
  teaser: /assets/images/portfolio/passport-th.jpg
sidebar:
  - title: "Quest"
    image: http://placehold.it/350x250
    image_alt: "logo"
    text: "Designer, First metaUser"
  - title: "Skills"
    text: "powaaaaaaaaaa"
---

yeah
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
