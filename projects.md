---
layout: default
title: "Projects"
---

# Projects

{% for project in site.projects %}
  - [{{ project.title }}]({{ project.url }}) - {{ project.date | date_to_string }}
{% endfor %}
