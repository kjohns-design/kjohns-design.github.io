---
layout: page
title: My Prosthetic Arm Project
---

# My Prosthetic Arm Project

This website documents my progress building an affordable prosthetic arm.

## Weekly Progress

{% assign posts = site.posts | sort: "date" | reverse %}

{% for post in posts %}
### [{{ post.title }}]({{ post.url }})

{{ post.excerpt }}

{% endfor %}
