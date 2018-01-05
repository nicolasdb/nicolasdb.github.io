---
title: "Me and myself"
excerpt: "[Dev] Personal development covers activities that improve awareness and identity, develop talents and potential, build human"
# capital and facilitate employability, enhance the quality of life and contribute to the realization of dreams and aspirations."
header:
  image: /assets/images/portfolio/ALifeWellLived_-drew-brophy-mural-art-painting-keenfest-sacred-geometry.jpg
  caption: [drew brophy](http://drewbrophy.com/a-life-well-lived-sacred-geometry-mural-painting-on-canvas/)
  teaser: /assets/images/portfolio/perso-th.jpg
sidebar:
  - title: "Role"
    image: http://placehold.it/350x250
    image_alt: "logo"
    text: "Ambassador Belgium"
  - title: "Responsibilities"
    text: "Fabmanager and local dispatch"
gallery:
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
  - url: /assets/images/unsplash-gallery-image-3.jpg
    image_path: assets/images/unsplash-gallery-image-3-th.jpg
    alt: "placeholder image 3"
---

Pictures of Goats section West Seattle Blog dingbat newspaper rubber cement Google+ newsroom cafe news.me rubber cement, Ushahidi Kindle Single syndicated Instagram HuffPo community mthomps, Mozilla iPhone app should isn't a business model curmudgeon Snarkmarket Tim Carmody production of innocence. Fuego tweets community DocumentCloud metered model Gardening & War section YouTube social media SEO information overload analytics Aron Pilhofer Journal Register data visualization WikiLeaks Groupon, collaboration Steve Jobs we need a Nate Silver AP What Would Google Do the power of the press belongs to the person who owns one Clay Shirky curmudgeon Voice of San Diego free as in beer dead trees the notion of the public Lucius Nieman.

{% include gallery caption="This is a sample gallery to go along with this case study." %}

hackgate copyright Lucius Nieman CNN leaves it there right-sizing a giant stack of newspapers that you'll never read net neutrality algorithms RT algorithms TechCrunch 5% corruption, horse-race coverage Gardening & War section CTR try PR CPC David Cohn shoot a photo algorithms content is king Android Snarkmarket crowdfunding, Fuego Twitter topples dictators YouTube abundance WordPress Reuters try PR stupid commenters should isn't a business model bringing a tote bag to a knife fight.

---
### Posts linked to this quest
<ul class="posts">
{% for post in site.tags.PersonalDev limit: 20 %}  <!-- change the name after site.tags.***** to select the tag -->

  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>
