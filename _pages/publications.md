---
layout: page
permalink: /publications/
title: publications
description: "<sup>1</sup> indicates joint first authors contributed equally； 
* indicates corresponding author"
years: [2023,2022,2021,2020,2019,2018,2017,2016,2015]
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
