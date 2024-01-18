---
layout: page
permalink: /seminars/
title: Seminars
description: Presentations at seminars.
years: [2024,2023,2022]
nav: false
nav_order: 1
---
<!-- _pages/seminars.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f seminars -q @*[year={{y}}]* %}
{% endfor %}

</div>
