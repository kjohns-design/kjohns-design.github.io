---
layout: home
---

# My Prosthetic Arm Project

This website documents my progress building an affordable prosthetic arm.

## Weekly Progress

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})

{{ post.excerpt }}

{% endfor %}


