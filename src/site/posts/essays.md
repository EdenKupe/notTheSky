---
title: Essays
layout: layouts/essays.njk
---

<ul id="collectionList" class="">
{%- for post in collections.essays -%}
  <li><i style="margin-right:1rem;margin-left:1rem;color:#ff8c8c" class="fas fa-moon"></i><a href="{{ post.url | url }}">{{ post.data.title }}</a></li>
{%- endfor -%}
</ul>