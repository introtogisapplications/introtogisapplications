---
layout: page
title: News
nav_exclude: 
description: A feed containing news and updates.
---

# Announcements

{% assign news = site.news | reverse %}
{% for new in news %}
{{ news }}
{% endfor %}
