---
layout: archive
title: My Work
permalink: /mywork/
tags: [mywork]
---

Here you’ll find a collection of dashboards and projects that reflect my growth as a Business Intelligence Analyst —  
each one combining curiosity, creativity, and a data-driven mindset.  

{% assign works = site.posts | where_exp: 'post', 'post.tags contains "dashboard"' | sort: 'date' | reverse %}

<h2>Projects & Dashboards</h2>
{% if works and works.size > 0 %}
<ul class="entries-grid">
  {% for post in works %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</ul>
{% else %}
<p><em>No dashboard-tagged posts found. Add <code>tags: [dashboard]</code> to your post front matter.</em></p>
{% endif %}
