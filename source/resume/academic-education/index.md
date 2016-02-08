---
layout: page
title: Academic Education
permalink: /resume/academic-education/
---

{% assign graduations = site.graduations | sort: "order" %}
{% for graduation in graduations reversed %}
  {{ graduation.output }}
{% endfor %}