---
title: /projects
layout: page
permalink: /projects
---

# Projects

{% for project in site.projects %}
# [{{ project.title }}]({{ project.url }})
<p>{{ project.description }}</p>
{% endfor %}
