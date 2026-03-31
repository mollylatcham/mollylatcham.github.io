---
layout: page
title: Curriculum Development
permalink: /curriculum-development/
nav: true
nav_order: 4
description: Curriculum development portfolio and artifacts.
---

{% assign cd_projects = site.projects | where: "category", "curriculum-development" | sort: "importance" %}

<h2>Curriculum Development Projects</h2>

<div class="row row-cols-1 row-cols-md-3">
  {% for project in cd_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>

