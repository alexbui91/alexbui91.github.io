---
layout: archive
title: "Projects"
permalink: /projects
author_profile: true
---

{% for post in site.projects reserved % %}
    {% include archive-single.html %}
{% endfor %}