---
layout: project
title: Projects/ tools development
---

<h1>Projects</h1>

<ul>
  {% for project in site.projects %}
    <li class="project-item">
      <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
      <img class="thumbnail" src="{{ project.thumbnail }}" alt="{{ project.title }} thumbnail">
      <p>{{ project.excerpt }}</p>
    </li>
  {% endfor %}
</ul>