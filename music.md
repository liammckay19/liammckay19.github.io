---
layout: default
title: Music
---

<ul>
{% for track in site.music %}
  <li>
    <a href="{{ track.url }}">{{ track.title }}</a>
    {% if track.short_description %}
    <ul><li>{{ track.short_description }}</li></ul>
    {% endif %}
  </li>
{% endfor %}
</ul>
