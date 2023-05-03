---
layout: articles
title: ENT Releases
permalink: /docs/ent-releases.html
key: page-sidebar-aside
cover: /img/docs/covers/ent-release.jpg
aside:
  toc: true
sidebar:
  nav: layouts
header:
   theme: dark

---

<div class="layout--articles">
<section class="my-5">
    <header><h3 id="page-layout"> 20 Deck Albums </h3></header>
  {%- include article-list.html articles= site.decks type='grid' size='lm' -%}
</section>

<section class="my-5">
    <header><h3 id="page-layout"> 3 x 10 Suits </h3></header>
  {%- include article-list.html articles= site.suits type='grid' size='lm' -%}
</section>


  <section class="my-5">
    <header><h3 id="page-layout"> 20 * 34 Cards </h3></header>
    {%- include article-list.html articles = site.cards type='grid' size='lm' -%}
  </section>


