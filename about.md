---
layout: page
title: About
description: A listing of all the course staff members.
---
# About

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
