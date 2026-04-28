---
layout: page
title: Zines
permalink: /zines.html
---

{% for project in site.zines %}
{% if project.show %}
- [{{ project.title }}]({{ site.url }}{{ project.url }}.html):
  {{ project.desc }}
{% endif %}
{% endfor %}
