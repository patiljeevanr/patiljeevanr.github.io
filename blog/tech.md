---
layout: default
title: "Tech Blogs"
---

# Tech Blogs

{% for post in site.posts %}
  {% if post.categories contains "tech" %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date_to_string }}
  {% endif %}
{% endfor %}
