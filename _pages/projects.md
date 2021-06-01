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
  {% include archive-single.html %}
{% endfor %}

Thesis Project
=====

{% for post in site.projects_btp reversed %}
  {% include archive-single.html %}
{% endfor %}

Robotics Projects
=====

{% for post in site.projects_agv reversed %}
  {% include archive-single.html %}
{% endfor %}

Course Projects
=====

{% for post in site.projects_course reversed %}
  {% include archive-single.html %}
{% endfor %}