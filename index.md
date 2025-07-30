---
layout: home
---

Bienvenido a mi laboratorio personal de análisis de malware, SIEM, IDS y ciberseguridad.

Aquí encontrarás tutoriales prácticos para detectar y analizar ataques reales.

---

## Últimos tutoriales

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%d %b %Y" }}</small>
    </li>
  {% endfor %}
</ul>
