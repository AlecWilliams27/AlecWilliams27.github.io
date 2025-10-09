---
layout: archive
title: My Artwork
permalink: /artwork/
tags: [artwork, education]
---

# 🎨 Welcome to My Creative Space

> **“A glimpse inside my mind — where data meets design and emotion becomes art.”**

Here I share my artistic side — bold ideas, abstract thoughts, and creative experiments.  
Every piece you see is part of how I process the world — through color, shape, and curiosity.  

This is more than artwork — it’s an open window into my creative process.

✨ *Created by Alec Williams*

{% assign artworks = site.posts | where_exp: 'post', 'post.tags contains "artwork" or post.categories contains "artwork"' | sort: 'date' | reverse %}

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
