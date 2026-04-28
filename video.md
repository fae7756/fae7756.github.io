---
layout: page
title: Video
permalink: /video.html
---

{% for project in site.video %}
{% if project.show %}
- [{{ project.title }}]({{ site.url }}{{ project.url }}.html):
  {{ project.desc }}
{% endif %}
{% endfor %}
