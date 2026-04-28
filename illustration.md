---
layout: page
title: Illustration
permalink: /illustration.html
---

{% for project in site.illustration %}
{% if project.show %}
- [{{ project.title }}]({{ site.url }}{{ project.url }}.html):
  {{ project.desc }}
{% endif %}
{% endfor %}
