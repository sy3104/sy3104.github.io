---
layout: page
permalink: /international/
title: International conferences
description: Presentations at international conferences.
years: [2024,2023,2022,2021]
nav: false
nav_order: 1
---
<!-- _pages/international.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f international -q @* %}
{% endfor %}

</div>
