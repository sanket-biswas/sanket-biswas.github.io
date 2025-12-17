---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

<h2>Preprints</h2>
<div class="publications">
{% bibliography --query @*[keywords~=preprint] %}
</div>

<h2>Theses</h2>
<div class="publications">
{% bibliography --query @*[keywords~=thesis] %}
</div>

<h2>Papers</h2>
<div class="publications">
{% bibliography --query @*[keywords~=paper] %}
</div>

<h2>Books</h2>
<div class="publications">
{% bibliography --query @*[keywords~=book] %}
</div>
