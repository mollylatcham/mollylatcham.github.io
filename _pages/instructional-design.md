---
layout: page
title: Instructional Design
permalink: /instructional-design/
nav: true
nav_order: 3
description: Instructional Design portfolio and case studies.
---

{% assign id_projects = site.projects | where: "category", "instructional-design" | sort: "importance" %}

<h2>Instructional Design Projects</h2>

<div class="row row-cols-1 row-cols-md-3">
  {% for project in id_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>

