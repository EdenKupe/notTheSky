---
title: Essays
layout: layouts/essays.njk
---

<ul id="collectionList" class="">
{%- for post in collections.essays -%}
  <li><i style="margin-right:1rem;margin-left:1rem;color:#ff8c8c" class="fas fa-moon"></i><a href="{{ post.url | url }}">{{ post.data.title }}</a><i style="margin-right:1rem;margin-left:1rem;color:#ff8c8c" class="fas fa-moon"></i></li>
{%- endfor -%}
</ul>

I write essays. Most of them are published over at [Heavy Blog is Heavy](www.heavyblogisheavy.com) and they are music related. However, I've made it my goal to start writing non-music related essays and this is where I'll publish them! Pretty simple, right? Hurray, simplicity!