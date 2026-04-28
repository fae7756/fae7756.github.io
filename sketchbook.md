---
layout: page
title: Sketchbook
permalink: /sketchbook.html
---

{% for project in site.sketchbook %}
{% if project.show %}
- [{{ project.title }}]({{ site.url }}{{ project.url }}.html):
  {{ project.desc }}
{% endif %}
{% endfor %}
