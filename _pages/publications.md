---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can find the full list of my articles on <u><a href="https://scholar.google.ch/citations?user=XcxXOJsAAAAJ&hl=en" target="_blank" style="color: black; text-decoration: underline;text-decoration-style: dotted;">**my Google Scholar profile**</a>.</u> Below is a list of selected publications:

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
