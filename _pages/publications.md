---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can find the full list of my articles on <u><a href="https://scholar.google.ch/citations?user=XcxXOJsAAAAJ&hl=en">**my Google Scholar profile**</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
