---
title: /projects
layout: page
permalink: /projects
---

# Projects


{% for project in site.projects %}
<div class="projects-entry">
<img src="{{ project.image | relative_url }}" alt="{{ project.title }} image" class="project-image">
<div class="project-details">
    <h1><a href="{{ project.url }}" class="no-underline">{{ project.title }}</a></h1>
    <i>{{ project.description }}</i>
</div>
</div>
{% endfor %}
