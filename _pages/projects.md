---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

Projects Done during Internships
=====

{% for post in site.projects_intern reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
