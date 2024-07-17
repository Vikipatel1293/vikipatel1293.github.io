---
layout: home
title: "Home"
---
Welcome to my website!

## Articles
{% for article in site.articles %}
- [{{ article.title }}]({{ article.url }})
{% endfor %}

## Blogs
{% for blog in site.blogs %}
- [{{ blog.title }}]({{ blog.url }})
{% endfor %}

## Projects
{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }})
{% endfor %}

## Resume
{% for resume in site.resume %}
- [{{ resume.title }}]({{ resume.url }})
{% endfor %}
