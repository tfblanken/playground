---
layout: page
permalink: /publications/
title: publications
description: in peer-reviewed journals
years: [2021, 2020, 2019, 2018, 2017, 2014]
nav: false
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
