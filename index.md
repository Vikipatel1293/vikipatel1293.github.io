---
layout: home
title: "Home"
---

Welcome to my website!

## Articles
<ul>
  {% for article in site.articles %}
    <li>
      <a href="{{ article.url }}">{{ article.title }}</a>
      <span>{{ article.date | date_to_string }}</span>
    </li>
  {% endfor %}
</ul>

## Blogs
<ul>
  {% for blog in site.blogs %}
    <li>
      <a href="{{ blog.url }}">{{ blog.title }}</a>
      <span>{{ blog.date | date_to_string }}</span>
    </li>
  {% endfor %}
</ul>

## Projects
<ul>
  {% for project in site.projects %}
    <li>
      <a href="{{ project.url }}">{{ project.title }}</a>
      <span>{{ project.date | date_to_string }}</span>
    </li>
  {% endfor %}
</ul>

## Resume
<ul>
  {% for resume in site.resume %}
    <li>
      <a href="{{ resume.url }}">{{ resume.title }}</a>
      <span>{{ resume.date | date_to_string }}</span>
    </li>
  {% endfor %}
</ul>
