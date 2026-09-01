---
layout: page
permalink: /publications/
title: publications
description: Selected publications and preprints by Xuting Zhang in computational biology, machine learning, protein modeling, and regulatory genomics.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}
{% include publication_legend.liquid %}

<div class="publications">

<h2 class="publication-section-title">peer-reviewed</h2>
{% bibliography --group_by none --query @*[status=published]* %}

<h2 class="publication-section-title">preprints</h2>
{% bibliography --group_by none --query @*[status=preprint]* %}

</div>
