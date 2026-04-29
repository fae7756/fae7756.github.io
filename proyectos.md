---
layout: page
title: Proyectos
permalink: /proyectos.html
---

{% for project in site.proyectos %}
{% if project.show %}
- [{{ project.title }}]({{ site.url }}{{ project.url }}.html):
  {{ project.desc }}
{% endif %}
{% endfor %}
