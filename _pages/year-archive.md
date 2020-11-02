---
layout: archive
permalink: /blog_posts/
title: "Blog posts"
author_profile: true
---

## Blogs

{% include base_path %}
## test1
{% for post in site.blog_posts %}
  {% include archive-single.html %}
{% endfor %}
