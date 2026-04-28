---
layout: page
title: Other Works
permalink: /work.html
---

{% for item in site.data.mediums %}
- [{{ item.name }}]({{ site.url }}{{ item.link }})
{% endfor %}
