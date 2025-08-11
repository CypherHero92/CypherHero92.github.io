---
layout: home
title: Red Team
permalink: /categories/red-team/
---

# Red Team

Posts de la categoría **Red Team**:

<ul>
  {% assign posts = site.categories['red-team'] %}
  {% for post in posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%d %b %Y" }}</small></li>
  {% endfor %}
</ul>

<p><a href="/">Volver a inicio</a></p>
