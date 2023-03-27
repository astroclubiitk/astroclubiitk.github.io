---
layout: page
title: Resources
subtitle: Confused where to start? We got your back!
cover-img: /assets/img/banner/resources.jpg
---

<ul class="pagination blog-pager resource-btn">
  {% for resource in site.resources limit:2 %}
  <li class="page-item">
    <a class="page-link" href="/resources/{{ resource.link }}" data-toggle="tooltip" data-placement="top" >{{ resource.button-text }}</a>
  </li>
  <br>
  {% endfor %}  
</ul>

<ul class="pagination blog-pager resource-btn">
  {% for resource in site.resources limit:3 offset:2 %}
  <li class="page-item">
    <a class="page-link" href="/resources/{{ resource.link }}" data-toggle="tooltip" data-placement="top" >{{ resource.button-text }}</a>
  </li>
  <br>
  {% endfor %}  
</ul>

<ul class="pagination blog-pager resource-btn">
  {% for resource in site.resources limit:3 offset:5 %}
  <li class="page-item">
    <a class="page-link" href="/resources/{{ resource.link }}" data-toggle="tooltip" data-placement="top" >{{ resource.button-text }}</a>
  </li>
  <br>
  {% endfor %}  
</ul>

<ul class="pagination blog-pager resource-btn">
  {% for resource in site.resources limit:2 offset:8 %}
  <li class="page-item">
    <a class="page-link" href="/resources/{{ resource.link }}" data-toggle="tooltip" data-placement="top" >{{ resource.button-text }}</a>
  </li>
  <br>
  {% endfor %}  
</ul>

<ul class="pagination blog-pager resource-btn">
  {% for resource in site.resources limit:1 offset:10 %}
  <li class="page-item">
    <a class="page-link" href="/resources/{{ resource.link }}" data-toggle="tooltip" data-placement="top" >{{ resource.button-text }}</a>
  </li>
  <br>
  {% endfor %}  
</ul>
