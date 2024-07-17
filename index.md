---
layout: home
title: "Home"
---

Welcome to my website!

## Articles
<ul>
  {% for post in site.articles %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date_to_string }}</span>
    </li>
  {% endfor %}
</ul>

## Blogs
<ul>
  {% for post in site.blogs %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date_to_string }}</span>
    </li>
  {% endfor %}
</ul>

## Projects
<ul>
  {% for post in site.projects %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date_to_string }}</span>
    </li>
  {% endfor %}
</ul>

## Resume
<ul>
  {% for post in site.resume %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date_to_string }}</span>
    </li>
  {% endfor %}
</ul>
