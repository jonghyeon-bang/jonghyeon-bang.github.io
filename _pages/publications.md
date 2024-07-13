---
layout: collection
permalink: /publication/
title: "Publications"
tok: true
toc_sticky: true
---

<div class="International">
  <h2>International</h2>
  {% for post in site.posts %}
    {% if post.categories contains "International" %}
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <p>{{ post.excerpt }}</p>
    {% endif %}
  {% endfor %}
</div>

<div class="Domestic">
  <h2>Domestic</h2>
  {% for post in site.posts %}
    {% if post.categories contains "Domestic" %}
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <p>{{ post.excerpt }}</p>
    {% endif %}
  {% endfor %}
</div>