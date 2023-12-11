---
title: Poems
layout: layouts/poems.njk
---

<ul id="collectionList" class="text-center mb-8 text-left text-xl w-7/12">
{%- for post in collections.poems -%}
  <li class=""><i style="margin-right:1rem;margin-left:1rem;color:#ff8c8c" class="fas fa-moon"></i><a href="{{ post.url | url }}">{{ post.data.title }}</a><i style="margin-right:1rem;margin-left:1rem;color:#ff8c8c" class="fas fa-moon"></i></li>
{%- endfor -%}
</ul>