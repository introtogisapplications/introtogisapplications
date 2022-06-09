---
layout: page
title: About
nav_exclude: true
description: A listing of all the course staff members.
---
# About

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
