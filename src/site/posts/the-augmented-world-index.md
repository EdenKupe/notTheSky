---
title: The Augmented World
layout: layouts/augmented.njk
---

<h4>An augmented introduction</h4>

In 2014, when my whole life was breaking apart, I wrote a piece of prose/flash fiction called [The Demented World](/posts/the-demented-world-index/). It was a really dark time in my life. It involved a relationship of many years ending, a relationship around which I had built my inner world. **The Demented World** is me burning that world to the ground, basically a tantrum, metaphorical furniture being thrown as my rage, betrayal, and self doubt were given flight. I didn’t sleep, I cried all day, and I wrote. Sometimes I really didn’t want to write but I couldn’t stop; some of the stuff in there is written from anguish.

But then, in 2017, I started **The Augmented World**. I didn’t intend it as a response to that previous piece of work; I was starting my infatuation with magic realism back then and wanted to give that place a venting vector. But then, when I sat down to actually write it, the title just flowed from my fingers and I realized that this was to be part of my healing process, already well under way back then. This paralleled my own psychological turn to magic realism as a way to combat nihilism, as a way to balance it with a brighter and more willful outlook on life.

Thus, **The Augmented World** is my attempt to imagine a more beautiful world, made beautiful because it has ugliness within it. It’s an attempt to reconnect with a naive, hopeful, gleeful side of myself. It’s also what I mentioned above; an homage to the greats of the genre and a place for me to let my flights of fancy take shape.

Below, you'll find all the pieces of it. It's a work in progress. Enjoy.

<hr class="iconHR">

<ul id="collectionList" class="">
{%- for post in collections.augmented -%}
  <li><span>//</span><a href="{{ post.url | url }}">{{ post.data.title }}</a></li>
{%- endfor -%}
</ul>
