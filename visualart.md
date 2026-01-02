---
layout: default
title: VisualArt
---

<ul>
{% for art in site.visualart %}
  <li>
    <a href="{{ art.url }}">
      {{ art.title }}
      <img src="{{ art.thumbnail | relative_url }}" width="300">
    </a>
  </li>
{% endfor %}
</ul>