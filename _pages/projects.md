---
layout: page
title: research
permalink: /research/
description: Selected research projects in intelligent transportation, traffic vision, and multimodal AI.
nav: true
nav_order: 1
horizontal: false
---

<div class="projects">
  <div class="row row-cols-1 row-cols-md-2">
  {% assign sorted_projects = site.projects | sort: "importance" %}
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
  </div>
</div>
