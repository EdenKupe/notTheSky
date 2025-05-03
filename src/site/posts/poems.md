---
title: Poems
layout: layouts/poems.njk
---

<ul id="collectionList" style="height: 680px;" class="mb-8 text-left text-xl w-7/12">
{%- for post in collections.poems -%}
  <li><span>//</span><a href="{{ post.url | url }}">{{ post.data.title }}</a></li>
{%- endfor -%}
</ul>