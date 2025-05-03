---
title: Ex Nihilo
layout: layouts/nihilo.njk
---

<h4>Out of nothing</h4>

**Ex Nihilo** is a science fiction, short story suite. What does that mean? It means that it’s made up of a series of short stories, some of them short enough to be considered “flash” literature, some of them not so much, who all share one universe. In this universe, a galactic empire called the Heart controls the galaxy, through culture, language and knowledge. In **Ex Nihilo**, I pay homage to many of my favorite science fiction tropes and genres. However, most of the reasoning behind writing this was just to get it out there; it was bothering me too much inside my brain. Select parts of this story suite have also been translated into music.

<iframe title="Ex nihilo album stream" style="border: 0; width: 30%; height: 120px;" src="https://bandcamp.com/EmbeddedPlayer/album=3293077651/size=large/bgcol=ffffff/linkcol=0687f5/tracklist=false/artwork=small/transparent=true/" seamless><a href="http://instar1.bandcamp.com/album/the-ex-nihilo-cycle">The **Ex Nihilo** Cycle by Instar</a></iframe>

Here’s a short intro before you read:

“Love is the ark appointed for the righteous,
Which annuls the danger and provides a way of escape.
Sell your cleverness and buy bewilderment.
Cleverness is mere opinion, bewilderment intuition.”

–Jalāl ad-Dīn Muhammad Rūmī

<ul id="collectionList" class="">
{%- for post in collections.nihilo -%}
  <li><span>//</span><a href="{{ post.url | url }}">{{ post.data.title }}</a></li>
{%- endfor -%}
</ul>