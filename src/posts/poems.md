---
title: Poems
layout: layouts/poems.njk
---

<ul id="collectionList">
{%- for post in collections.poems -%}
  <li><i class="fas fa-moon"></i><a href="{{ post.url | url }}">{{ post.data.title }}</a></li>
{%- endfor -%}
</ul>
