---
layout: single
title: My Dashboards
permalink: /dashboards/
tags: [dashboards, education, portfolio]
---

# 📊 My Dashboard Journey  

> **“Where logic meets creativity — and data starts to speak.”**

At **TripleTen**, I learned how to see data differently.  
Every dashboard I built — from e-commerce and restaurant analytics to Airbnb and Superstore reports —  
helped me develop a unique eye for storytelling through visuals.  

What started as coursework soon became a passion:  
taking rows of numbers and shaping them into meaningful, dynamic stories.  

Here you’ll find a collection of dashboards that reflect my growth as a Business Intelligence Analyst —  
each one combining curiosity, creativity, and a data-driven mindset.  

✨ *Created by Alec Williams*

{% assign dashboards = site.posts | where_exp: 'post', 'post.tags contains "dashboard"' | sort: 'date' | reverse %}

<h2>Dashboards</h2>
{% if dashboards and dashboards.size > 0 %}
<ul class="entries-grid">
  {% for post in dashboards %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</ul>
{% else %}
<p><em>No dashboard posts found. Ensure your posts have <code>tags: [dashboard]</code> in front matter.</em></p>
{% endif %}
