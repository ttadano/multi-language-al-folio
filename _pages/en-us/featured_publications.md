---
page_id: featured_publications
layout: page
title: Featured publications
description:
permalink: /featured_publications/
---

<!-- _pages/publications.md -->
<div class="publications">
<h2>Refereed Papers</h2>
{% bibliography --query @article[year>=2023 && review_article != true] %}

<h2>Review Articles</h2>
{% bibliography --query @article[year>=2023 && review_article = true && japanese != true] %}

</div>
