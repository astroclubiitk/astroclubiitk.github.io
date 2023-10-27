---
layout: page
title: Projects
subtitle: A one-stop resource place for your project undertakings.
cover-img: /assets/img/banner/projects.jpeg
---

<ul class="pagination blog-pager">
  {% for project in site.projects limit:3 %}
  <li class="page-item">
    <a class="page-link" href="{{ project.link }}" data-toggle="tooltip" data-placement="top" >{{ project.button-text }}</a>
  </li>
  <br>
  {% endfor %}  
</ul>

<ul class="pagination blog-pager">
  {% for project in site.projects limit:1 %}
  <li class="page-item">
    <a class="page-link" href="{{ project.link }}" data-toggle="tooltip" data-placement="top" >{{ project.button-text }}</a>
  </li>
  <br>
  {% endfor %}  
</ul>
