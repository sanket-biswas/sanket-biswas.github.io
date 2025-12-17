---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

<div class="publications">

  <h2 class="pub-section">Papers</h2>
  {% bibliography --query @*[keywords~=paper] %}

  <h2 class="pub-section">Preprints</h2>
  {% bibliography --query @*[keywords~=preprint] %}

  <h2 class="pub-section">Thesis</h2>
  {% bibliography --query @*[keywords~=thesis] %}

  <h2 class="pub-section">Books</h2>
  {% bibliography --query @*[keywords~=book] %}

</div>
