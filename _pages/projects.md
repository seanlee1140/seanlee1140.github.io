---
permalink: /projects/
title: "Projects"
excerpt: "A collection of my projects."
layout: single
# collection: projects
# entries_layout: grid
classes: wide
author_profile: false
sidebar:
  nav: "project_sidebar"
---

This is a collection of brief summaries of my previous projects. For more details, please visit the individual project pages.





{% for project in site.projects %}

<div class="project-entry" style="margin-bottom: 3em;">
  <h2 class="archive__item-title no_toc">
    <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
  </h2>

  {{ project.excerpt }}

  {% if project.header.teaser %}
    <div class="project-image" style="margin-top: 1em;">
      <img src="{{ project.header.teaser | relative_url }}" alt="{{ project.title }}" style="width: 100%; height: auto; max-width: 600px;">
    </div>
  {% endif %}
</div>

{% endfor %}
