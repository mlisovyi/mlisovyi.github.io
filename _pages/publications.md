---
layout: page
permalink: /publications/
title: publications
description: I have changed my official first name from Mykhailo to Mischa in the meantime 😄
years: [2017,2016, 2015, 2014, 2013,2010]
nav: true
nav_order: 4
---
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
