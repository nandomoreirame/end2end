---
layout: page
title: Professional experience
permalink: /resume/professional-experience/
---

{% assign experiences = site.experiences | sort: 'meta.admissiondate' | reverse %}
{% for experience in experiences reversed %}
  {{ experience.output }}
{% endfor %}