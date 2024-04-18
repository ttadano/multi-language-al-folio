---
page_id: full_publications
layout: page
title: Full publication list
permalink: /full_publications/
description:
---

<!-- _pages/full_publications.md -->
<div class="publications">
<h2>Refereed Papers</h2>
{% bibliography --query @article[review_article != true] %}

<h2>Review Articles</h2>
{% bibliography --query @article[review_article = true && japanese != true] %}

</div>
