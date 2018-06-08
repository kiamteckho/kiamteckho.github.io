---
layout: page
title: Portfolio
permalink: /portfolio/
---

<ul>
  {% for image in site.static_files %}
      {% if image.path contains 'portfolio' %}
          <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
      {% endif %}
  {% endfor %}
</ul>
