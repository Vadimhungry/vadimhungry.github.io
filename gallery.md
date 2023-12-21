---
layout: default
title: Gallery
permalink: /gallery/
---
# Gallery
## just random photos 
<div>
{% for image in site.static_files %}
  {% if image.path contains 'assets/img/gallery' %}
    <img src="{{ image.path }}" alt="">
  {% endif %}
{% endfor %}
</div>
