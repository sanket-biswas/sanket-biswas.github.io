---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

<div class="publications">

## Papers
{% bibliography --query @*[keywords~=paper] --group_by year --group_order descending %}

## Books
{% bibliography --query @*[keywords~=book] --group_by year --group_order descending %}

## Preprints
{% bibliography --query @*[keywords~=preprint] --group_by year --group_order descending %}

## Theses
{% bibliography --query @*[keywords~=thesis] --group_by year --group_order descending %}

</div>
