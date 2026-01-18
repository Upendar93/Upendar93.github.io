---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% for project in site.projects %}
## {{ project.title }}

{{ project.excerpt }}

[View Project →]({{ project.url }})

---
{% endfor %}
