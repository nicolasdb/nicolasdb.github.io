---
layout: page
show_meta: false
title: "Style your life!"
subheadline: "Layer of onions"
sidebar: right
breadcrumb: false
header:
    image_fullwidth: "design2/boxed-water-is-better-rXJXsecq8YU-unsplash.jpg"
    title: design2
    caption: Photo by Boxed Water Is Better on Unsplash
    caption_url: https://unsplash.com/@boxedwater?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText
permalink: "/design2/"
---
<ul>
    {% for post in site.categories.design2 %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>


Photo by <a href="https://unsplash.com/@boxedwater?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Boxed Water Is Better</a> on <a href="https://unsplash.com/wallpapers/nature/snow?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  