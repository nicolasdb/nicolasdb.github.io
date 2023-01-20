---
layout: page
show_meta: false
title: "Style your life!"
subheadline: "Layer of onions"
header:
   image_fullwidth: "header_unsplash_6.jpg"
permalink: "/design2/"
---
<ul>
    {% for post in site.categories.design2 %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>