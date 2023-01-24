---
layout: page
show_meta: false
title: "My journey of turning a passion into a career,"
subheadline: "from Making Things"
sidebar: 
breadcrumb: false
header:
    image_fullwidth: "make0.webp"
    title: 
permalink: "/design/"
---

Welcome! I'm excited to show you the projects and tutorials I've made and developed over my 10 years as a maker and fablab manager. Here, you'll find guides on building and maintaining machines, CAD and CAM software, electronics, Arduino, and more.

I'm passionate about making things and I'm excited to share my knowledge with you. Whether you're experienced or just starting out, I hope you'll find something useful and inspiring. I try to provide clear, concise, and easy-to-follow instructions, and to share my experiences and mistakes.

If you need help, please reach out. I'm always happy to help and learn from others.

Thank you for visiting, and happy making!


<ul>
    {% for post in site.categories.make %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>