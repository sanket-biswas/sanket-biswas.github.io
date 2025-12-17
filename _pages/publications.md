---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

<div class="publications">

  <section class="pub-block">
    <h2 class="pub-section">Papers</h2>
    {% bibliography --query @*[keywords~=paper] %}
  </section>

  <section class="pub-block">
    <h2 class="pub-section">Preprints</h2>
    {% bibliography --query @*[keywords~=preprint] %}
  </section>

  <section class="pub-block">
    <h2 class="pub-section">Thesis</h2>
    {% bibliography --query @*[keywords~=thesis] %}
  </section>

  <section class="pub-block">
    <h2 class="pub-section">Books</h2>
    {% bibliography --query @*[keywords~=book] %}
  </section>

</div>
