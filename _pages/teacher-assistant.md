---
layout: archive
title: "Teacher Assistant Experience"
permalink: /teacher-assistant/
author_profile: true
---

<!-- {% include base_path %} -->
{% for post in site.teacher_assistant reversed %}
  <a href="{{post.syllabus}}" target="_blank">{{post.title}}</a>
{% endfor %}
