---
page_id: full_publications
layout: page
title: 全論文リスト
permalink: /full_publications/
description:
---

<!-- _pages/full_publications.md -->
<div class="publications">
<h2>論文</h2>
{% bibliography --query @article[review_article != true] %}

<h2>解説記事</h2>
{% bibliography --query @article[review_article = true] %}

</div>
