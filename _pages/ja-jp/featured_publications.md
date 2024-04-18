---
page_id: featured_publications
layout: page
title: 主要論文
description:
permalink: /featured_publications/
---

<!-- _pages/publications.md -->
<div class="publications">
<h2>論文</h2>
{% bibliography --query @article[year>=2023 && review_article != true] %}

<h2>解説記事</h2>
{% bibliography --query @article[year>=2023 && review_article = true] %}

</div>
