---
layout: page
title: Projects
permalink: /projects/
---

## My Projects
<ul>
  {% for project in site.projects %}
    <li><a href="{{ project.url }}">{{ project.title }}</a></li>
  {% endfor %}
</ul>
