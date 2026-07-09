---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 2
description: Selected machine learning, NLP, recommendation systems, and LLM-based projects demonstrating practical AI engineering experience.
display_categories: [featured, machine-learning, nlp]
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endfor %}
{% else %}
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
{% endif %}
</div>