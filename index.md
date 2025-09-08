---
layout: home
title: Home
---

# Welcome! I'm Vikas Fugoki 👋

I'm a passionate **Developer & Tech Enthusiast** who loves building innovative solutions and sharing knowledge with the community.

## About Me

- 💻 **Full-Stack Developer** with expertise in modern web technologies
- 🚀 **Problem Solver** who enjoys tackling complex challenges
- ✍️ **Technical Writer** sharing insights through tutorials and blogs
- 🌱 **Continuous Learner** always exploring new technologies and best practices

## What I Do

### 🔧 **Development**
Building scalable web applications using cutting-edge technologies like React, Node.js, Python, and cloud platforms.

### 📝 **Technical Writing**  
Sharing my learning journey and helping others through detailed tutorials and project walkthroughs.

### 🤝 **Community Engagement**
Contributing to open-source projects and mentoring fellow developers.

## Featured Skills

- **Frontend**: React, JavaScript, HTML5, CSS3, TypeScript
- **Backend**: Node.js, Python, Express, Django
- **Database**: MongoDB, PostgreSQL, MySQL
- **Cloud**: AWS, Docker, Kubernetes
- **Tools**: Git, VS Code, Linux, Agile

## Latest Blog Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
  <br><small>{{ post.excerpt | strip_html | truncate: 100 }}</small>
{% endfor %}

[View all posts →]({{ site.baseurl }}/blog)

## Current Focus

🔥 **Currently working on**: [Your current project or learning focus]  
📚 **Learning**: [Technologies you're currently exploring]  
🎯 **Goals for 2024**: [Your professional goals]

---

## Let's Connect!

I'm always excited to connect with fellow developers and tech enthusiasts. Feel free to reach out!

- 📧 **Email**: [your.email@example.com](mailto:your.email@example.com)
- 💼 **LinkedIn**: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)  
- 🐙 **GitHub**: [github.com/vikasfugoki123](https://github.com/vikasfugoki123)
- 🐦 **Twitter**: [@yourusername](https://twitter.com/yourusername) _(optional)_

> "Code is poetry written in logic, and every bug is just a plot twist waiting to be resolved." - Vikas Fugoki
