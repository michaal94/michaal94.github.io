---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my articles on <a href="https://scholar.google.com/citations?user=m7yX5TYAAAAJ&hl=en">my Google Scholar profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include publication-basic.html %}
{% endfor %}
