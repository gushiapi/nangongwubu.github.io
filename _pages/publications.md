---
layout: page
permalink: /publications/
title: publications
description: 
years: [2021,2020,2019,2018,2017,2016,2015]
nav: true
---
See [Google Scholar](https://scholar.google.com/citations?hl=en&user=9_jlOXUAAAAJ) for the full publication list.

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
