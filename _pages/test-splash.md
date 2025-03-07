---
title: "Welcome"
layout: splash
permalink: /test-splash/
date: 2024-03-02T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/bg.jpg
  actions:
    - label: "Getting Started"
      url: "/about/"
  
excerpt: "Check out the Quick Start Guide below"
intro:
  - excerpt: 'Check out what we have to offer:'
feature_row:
  - image_path: /assets/images/lock.jpg
    
    alt: "placeholder image 1"
    title: "Projects"
    excerpt: "Click here to see the latest project we are working on."
  - image_path: /assets/images/hoodie.jpg
    alt: "placeholder image 2"
    title: "Blog"
    excerpt: "Check out our latest blog post."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/desk.jpg
    title: "Gear"
    excerpt: "Best deals on gear."
feature_row2:
  - image_path: /assets/images/test-image-2.jpg
    alt: "placeholder image 2"
    title: "Left Aligned Feature"
    excerpt: 'Left aligned feature row with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/test-image-2.jpg
    alt: "placeholder image 2"
    title: "Right Aligned Feature"
    excerpt: 'Right aligned feature row with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/test-image-2.jpg
    alt: "placeholder image 2"
    title: "Centered Feature"
    excerpt: 'Centered feature row with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}



{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
