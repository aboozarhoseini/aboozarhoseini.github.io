---
layout: default
title: Welcome to My Website
---

# Welcome to My Website

Hello! I'm Aboozar Hoseini. This is my personal website built with GitHub Pages and Jekyll.

## About This Site

This site uses the Hacker theme. Here you can find my projects, blog posts, and more.

## Latest Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}