---
layout: page
permalink: /publications/
title: publications
years: [2017,2016, 2015, 2014, 2013,2010]
nav: true
nav_order: 1
---
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
