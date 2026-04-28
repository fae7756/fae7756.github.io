---
layout: page
title: Sound Art
permalink: /soundart.html
---

{% for project in site.soundart %}
{% if project.show %}
- [{{ project.title }}]({{ site.url }}{{ project.url }}.html):
  {{ project.desc }}
{% endif %}
{% endfor %}
