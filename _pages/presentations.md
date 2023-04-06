---
layout: page
permalink: /presentations/
title: Presentations
description: Presentations at international and domestic conferences.
years: [2023,2022]
nav: false
nav_order: 1
---
<!-- _pages/presentations.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
