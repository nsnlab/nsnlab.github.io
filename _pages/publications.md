---
layout: page
permalink: /publications/
title: publications
description: publications in reverse chronological order.
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --query @*[year>=2016] %}

<h2 class="bibliography">2015 and earlier</h2>
<ol class="bibliography">
{% bibliography --query @*[year<=2015] --group_by none %}
</ol>

</div>
