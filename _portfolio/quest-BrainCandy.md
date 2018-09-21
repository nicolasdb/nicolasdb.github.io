---
title: "BrainCandy"
excerpt: "[Event] Between science and entertainment - A Collective Youtube night"
header:
  # image: /assets/images/portfolio/gami.jpg
  teaser: /assets/images/portfolio/braincandy-th.jpg

---
### Because we want to share IRL

I spent so much time on front of the screen, discovering new channels on youtube, watching a lot of tv-series and movies, documentary, ...   
There is this time where I get so excited by what I just learn, It's so cool and awesome, I want to do it to, I want to share and talk about it with others... but I'm home alone.  
Internet is great, we can access to so much.  
But it's still a lonely process.  
I wanted to create this moment, where we can share these video, watch them together and talk about them.

## What and Why BrainCandy?

As I stand out here in the wonders of the unknown at Hadley, I sort of realize there’s a fundamental truth to our nature, Man must explore . . . and this is exploration at its greatest.
We are all connected; To each other, biologically. To the earth, chemically. To the rest of the universe atomically.

{% include gallery caption="This is a sample gallery to go along with this case study." %}

Houston, Tranquility Base here. The Eagle has landed.
As we got further and further away, it [the Earth] diminished in size. Finally it shrank to the size of a marble, the most beautiful you can imagine. That beautiful, warm, living object looked so fragile, so delicate, that if you touched it with a finger it would crumble and fall apart. Seeing this has to change a man.

![gification](https://78.media.tumblr.com/5db78ee8363fa38efd3f1051447875fa/tumblr_nyo13brVkP1v096cfo1_500.gif)

this is a work in Progress, loading ....

---
### Posts linked to this quest
<ul class="posts">
{% for post in site.tags.braincandy limit: 20 %}  <!-- change the name after site.tags.***** to select the tag -->
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>
