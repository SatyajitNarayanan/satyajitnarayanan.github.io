---
layout: archive
title: Projects
permalink: /projects/
author_profile: true
collection: projects
classes: wide
image: "/images/coverpicture.jpeg"
---

{% for post in site.projects reversed limit:2 %}
  {% include archive-single.html type="grid"  %}
{% endfor %}
