---
layout: page
subheadline: "Header"
title: "Jaaga Startup"
teaser: "India's oldest collaborative coworking community"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/headers/"
---
<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>