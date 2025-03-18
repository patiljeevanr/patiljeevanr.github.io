---
layout: default
title: "Personal Blogs"
---

# Personal Blogs

{% for post in site.posts %}
  {% if post.categories contains "personal" %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date_to_string }}
  {% endif %}
{% endfor %}
