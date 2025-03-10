---
layout: posts
title: "The Hack Log: Documenting My Cybersecurity & Hacking Journey"
permalink: /blog/
author_profile: true
---

Welcome to my blog! This is where I document my journey in **cybersecurity, ethical hacking, and penetration testing**.

## 🔥 Latest Posts
{% for post in site.posts %}
- 📌 **[{{ post.title }}]({{ post.url | relative_url }})** ({{ post.date | date: "%B %d, %Y" }})
{% endfor %}

## 🏴‍☠️ Categories
Browse blog posts by topic:

<div class="categories-columns">
  {% assign categories = site.categories | sort %}
  {% for category in categories %}
    <div class="category-link">
      🔍 **[{{ category[0] }}](/categories/{{ category[0] }}/)** ({{ category[1].size }} posts)
    </div>
  {% endfor %}
</div>

## 📂 Archives
Looking for something specific? Check out the [archives](/year-archive/).

