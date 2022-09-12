---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Here you can find more details on ongoing projects.

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-project.html %}
{% endfor %}
