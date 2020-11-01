---
layout: archive
permalink: /year-archive/
title: "Blog posts"
author_profile: true
---

## Blogs

{% include base_path %}
## test1
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
