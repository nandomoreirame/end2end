---
layout: page
title: Resume
permalink: /resume/
---


## About {{ site.title }}

{% assign current_year = 'now' | date: '%Y' %}

I'm {{ (current_year) | minus:1984 }} years old. Was born in Porto Alegre - Brazil. I'm married to Daniela Priscila Lins. We had two beautiful children Pedro Henrique Lins Vieira and Ana Carolina Lins Vieira. I'm envolved with systems development since 2006.


## Purpose

Create new and better concepts with design patterns and best practices for application development. Working together with a team focused on better solution for applications, independent of the language used and the plataforma that the system will be used.

## Academic education
{% include education.html %}
<hr />
## Professional experience
{% include experience.html %}
<hr />
## Skills
{% include skills.html %}