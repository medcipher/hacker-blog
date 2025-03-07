---
title: "Test Splash Page"
layout: splash
permalink: /test-splash/
date: 2024-03-02T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/bg.jpg
  actions:
    - label: "Learn More"
      url: "/about/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "This is a test splash page using Minimal Mistakes Jekyll theme."
intro:
  - excerpt: 'This is an introduction section with sample content. Centered with `type="center"`'
feature_row:
  - image_path: /assets/images/test-image-1.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 1"
    title: "Feature 1"
    excerpt: "This is some sample content using **Markdown** formatting."
  - image_path: /assets/images/test-image-2.jpg
    alt: "placeholder image 2"
    title: "Feature 2"
    excerpt: "Another section with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/test-image-3.jpg
    title: "Feature 3"
    excerpt: "More placeholder content with **Markdown** formatting."
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
