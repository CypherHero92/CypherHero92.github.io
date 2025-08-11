---
layout: home
title: Consejos de Seguridad
permalink: /categories/consejos/
---

# Consejos de Seguridad

Posts de la categoría **Consejos**:

<ul>
  {% assign posts = site.categories['consejos'] %}
  {% for post in posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%d %b %Y" }}</small></li>
  {% endfor %}
</ul>

<p><a href="/">Volver a inicio</a></p>
