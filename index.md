---
layout: home
title: Home
---

# Welcome to My Portfolio

Hi, I'm **Your Name**, a passionate [Your Profession] with expertise in [Your Skills]. 

I love working on [Your Interests] and sharing my journey through code and writing.

## What I Do

- 💻 **Development**: Building modern web applications
- ✍️ **Writing**: Sharing insights and tutorials through my blog  
- 🚀 **Innovation**: Always exploring new technologies

## Latest Blog Posts

Check out my recent thoughts and tutorials:

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View all posts →](/blog)

---

📫 **Get in touch**: [your.email@example.com](mailto:your.email@example.com) | [LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername)
