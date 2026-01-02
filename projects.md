---
layout: default
title: Projects
---


<h2>Audio Visual Programming</h2>
{% for project in site.projects %}
  {% if project.type == "AV" %}
  <li>
    <a href="{{ project.url }}">{{ project.title }}</a>
  </li>
  {% endif %}
{% endfor %}

<br>
<h2>Computer Science</h2>
{% for project in site.projects %}
  {% if project.type == "CS" %}
  <li>
    <a href="{{ project.url }}">{{ project.title }}</a>
  </li>
  {% endif %}
{% endfor %}
