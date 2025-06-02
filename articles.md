---
layout: default
title: Articles & Papers
permalink: /articles/
---

# Articles & Papers

{% for post in site.articles %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
  <p>{{ post.excerpt }}</p>
{% endfor %}