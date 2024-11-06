---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2024, 2023]
nav: true
---

#### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>
