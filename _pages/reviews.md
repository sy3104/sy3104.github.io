---
layout: page
permalink: /reviews/
title: Review articles
description: Publications in reversed chronological order.
years: [2023,2022]
nav: false
nav_order: 1
---
<!-- _pages/reviews.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f reviews -q @*[year={{y}}]* %}
{% endfor %}

</div>
