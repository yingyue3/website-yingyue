---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

A reverse-chronological history of research and software projects I have
worked on. Each entry summarizes the goal, my contribution, and links to
relevant publications, code, or talks where available.

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
