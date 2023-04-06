---
layout: page
permalink: /domestic/
title: Domestic conferences
description: Presentations at domestic conferences.
years: [2023,2022,2021]
nav: false
nav_order: 1
---
<!-- _pages/domestic.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f domestic -q @*[year={{y}}]* %}
{% endfor %}

</div>
