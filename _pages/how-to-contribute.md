---
title: "How to contribute"
# layout: "default"
permalink: /howto/
# date: 2016-02-24T03:02:20+00:00
---

# Introduction

### Write something nice here!

>First off, thank you for considering contributing to Active Admin. It's people like you that make Active Admin such a great tool.  
[source: [Active Admin](https://github.com/activeadmin/activeadmin/blob/master/CONTRIBUTING.md)]

Link to opensource guide, specific to  
[why contributing?](https://opensource.guide/how-to-contribute/)

### Explain what kinds of contributions you are looking for.

- [issue #18](https://github.com/nicolasdb/nicolasdb.github.io/issues/18) : un picto "quest" pour signaler le type de contenu d'une page.
- ~~[issue #19](https://github.com/nicolasdb/nicolasdb.github.io/issues/19) : affichage des lien html non visible.~~ - closed


### Posts linked to this quest
<ul class="posts">
{% for post in site.tags.contribute limit: 20 %} <!-- change the name after site.tags.***** to select the tag -->
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>
