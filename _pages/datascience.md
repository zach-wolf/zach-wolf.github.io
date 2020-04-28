---
layout: archive
permalink: /data-science/
title: "Data Science Portfolio"
author_profile: false  
header:
  image: "/images/tennessee.jpeg"
---

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
