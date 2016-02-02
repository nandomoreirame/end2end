---
layout: page
title: Academic Education
permalink: /resume/academic-education/
---

{% assign graduations = site.graduations | sort: 'url', 'last' %}
{% for graduation in graduations %}
  {{ graduation.output }}
{% endfor %}