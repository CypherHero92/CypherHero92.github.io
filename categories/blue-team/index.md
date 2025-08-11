---
layout: home
title: Blue Team
permalink: /categories/blue-team/
---

# Blue Team

Posts de la categoría **Blue Team**:

<ul>
  {% assign posts = site.categories['blue-team'] %}
  {% for post in posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%d %b %Y" }}</small></li>
  {% endfor %}
</ul>

<p><a href="/">Volver a inicio</a></p>
