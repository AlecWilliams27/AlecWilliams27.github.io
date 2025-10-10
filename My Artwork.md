---
layout: archive
title: My Artwork
permalink: /artwork/
tags: [artwork, education]
---

> ##### A glimpse inside my mind — where emotion becomes art 

This space isn’t about professionalism or polished presentations — it’s about raw creativity and authentic expression. Here, I open the door to the part of me that dreams in color, thinks in shapes, and turns emotion into art. Every piece you see is a reflection of how I process the world around me — bold ideas, abstract thoughts, and unfiltered imagination brought to life.

This is the core of who I am and what drives everything I do. It’s proof that creativity isn’t something I leave at the door — it’s something I carry into every space I step into, blending art, emotion, and purpose into everything I create.
I hope these pieces speak to the parts of you that words can’t reach — and remind you of the beauty that exists in raw, honest expression.

✨ *Created by Alec Williams*

{% assign artworks = site.categories.artwork | sort: 'date' | reverse %}

<h2>Artwork</h2>
{% if artworks and artworks.size > 0 %}
<ul class="entries-grid">
  {% for post in artworks %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</ul>
{% else %}
<p><em>No artwork posts found. Add <code>tags: [artwork]</code> or <code>categories: [artwork]</code> to your posts.</em></p>
{% endif %}
