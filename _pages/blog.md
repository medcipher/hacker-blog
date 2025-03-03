---
layout: posts
title: "Blog"
permalink: /blog/
author_profile: true
---

Welcome to my blog! This is where I document my journey in **cybersecurity, ethical hacking, and penetration testing**.

## 🔥 Latest Posts
{% for post in site.posts %}
- 📌 **[{{ post.title }}]({{ post.url }})** ({{ post.date | date: "%B %d, %Y" }})
{% endfor %}

## 🏴‍☠️ Categories
Browse blog posts by topic:
{% assign categories = site.categories | sort %}
{% for category in categories %}
- 🔍 **[{{ category[0] }}](/categories/{{ category[0] }}/)** ({{ category[1].size }} posts)
{% endfor %}

## 📂 Archives
Looking for something specific? Check out the [archives](/year-archive/).

