---
layout: page
permalink: /publications/
title: publications
description: Preprints and published papers.
nav: true
nav_order: 1
---

{% include bib_search.liquid %}

<h2 id="preprints">Preprints</h2>

<div class="publications">
  {% bibliography --query @unpublished %}
</div>

<h2 id="published-papers">Publications</h2>

<div class="publications">
  {% bibliography --query @article %}
</div>