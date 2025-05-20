---
layout: page
permalink: /papers/
title: Papers
description: Publications in reversed chronological order.
years: [2025,2024,2023,2022]
nav: false
nav_order: 1
---
<!-- _pages/papers.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
