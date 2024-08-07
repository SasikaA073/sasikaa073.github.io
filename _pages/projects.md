---
layout: page
title: projects
permalink: /projects/
description: 
nav: true
nav_order: 3
display_categories: ["Data + Machine Learning", "Hardware", "Web Development", "Telecommunication"] # "Ongoing", 
horizontal: false
---


<!-- pages/projects.md -->
<div class="projects">

<!-- Create a category list for projects  -->


<h5>
{% for category in page.display_categories %}
  {% assign encoded_category = category | url_encode %}
  <a class="" id="{{ encoded_category }}" href="#{{ encoded_category }}">{{ category }}</a>
  {% if forloop.last == false %}&nbsp;&nbsp;•&nbsp;&nbsp;{% endif %}
{% endfor %}</h5>




{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  
  {% assign encoded_category = category | url_encode %}
  <a id="{{ encoded_category }}" href="#{{ encoded_category }}">
    <h2 class="category">{{ category }}</h2>
  </a>

  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>
