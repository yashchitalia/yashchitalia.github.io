---
layout: single
title: Ongoing Research
permalink: /research/
author_profile: true
---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
{% include base_path %}
### Pediatric Neuroendoscope

{% for post in site.publications.neuro reversed %}
  {% include archive-single.html %}
{% endfor %}