---
layout: page
title: Materials
permalink: /materials/
---
# Downloadable Materials

{% for file in site.static_files %}
  {% if file.path contains 'materials/' %}
- [{{ file.name }}]({{ file.path | relative_url }})
  {% endif %}
{% endfor %}
