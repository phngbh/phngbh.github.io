---
layout: project
title: Data visualization
---

<h1>Data Visualization Gallery</h1>

<p style="font-size: 17px;">
  Excel-generated barplots are boring. In this page I will keep sharing the codes for eye-catching plots that I made during several projects, which I think are interesting and might be useful in specific situations, mostly in bioinformatics and computational biomedicine research.  
  Hope they give you ideas for your projects.
</p>

<ul>
  {% for data_viz_item in site.data_viz %}
    <li class="project-item">
      <h3><a href="{{ data_viz_item.url }}">{{ data_viz_item.title }}</a></h3>
      <img class="thumbnail" src="{{ data_viz_item.thumbnail }}" alt="{{ data_viz_item.title }} thumbnail">
      <p>{{ data_viz_item.excerpt }}</p>
    </li>
  {% endfor %}
</ul>