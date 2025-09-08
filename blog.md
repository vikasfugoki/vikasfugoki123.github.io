---
layout: page
title: Blog
permalink: /blog/
---

# My Blog

Welcome to my blog where I share insights about development, technology, and my learning journey.

## All Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}* | {% if post.tags %}{% for tag in post.tags %}`{{ tag }}` {% endfor %}{% endif %}

{{ post.excerpt }}

[Read more →]({{ post.url }})

---
{% endfor %}

## Categories

{% assign tags = site.posts | map: 'tags' | join: ',' | split: ',' | uniq %}
{% for tag in tags %}
- [{{ tag }}](/blog/tag/{{ tag | slugify }})
{% endfor %}
