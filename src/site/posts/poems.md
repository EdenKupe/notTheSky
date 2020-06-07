---
title: Poems
layout: layouts/poems.njk
---

<ul id="collectionList">
{%- for post in collections.poems -%}
  <li><i style="margin-right:1rem;margin-left:1rem;color:#ff8c8c" class="fas fa-moon"></i><a href="{{ post.url | url }}">{{ post.data.title }}</a></li>
{%- endfor -%}
</ul>
