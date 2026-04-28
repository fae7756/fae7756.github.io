---
layout: page
title: Photography
permalink: /photography.html
---

{% for project in site.photography %}
{% if project.show %}
- [{{ project.title }}]({{ site.url }}{{ project.url }}.html):
  {{ project.desc }}
{% endif %}
{% endfor %}
