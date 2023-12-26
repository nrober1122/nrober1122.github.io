---
layout: archive
permalink: /commlab/
author_profile: true
related: false
---

{% include base_path %}

As an [AeroAstro Communications Lab](https://mitcommlab.mit.edu/aeroastro/) fellow, I develop material to help students in our department with various aspects of technical communication.
Among these materials are blog posts and CommKit articles, which are catalogued here.

# Blog Posts
---
{% for post in site.posts reversed %}
  {% if post.type contains "blog" %}
    {% include archive-single-post.html %}
  {% endif %}
{% endfor %}

# CommKit Articles
---
{% for post in site.posts reversed %}
  {% if post.type contains "commkit" %}
    {% include archive-single-post.html %}
  {% endif %}
{% endfor %}