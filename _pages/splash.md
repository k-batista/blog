---
title: "Hello, world!"
layout: splash
permalink: /
header:
  # overlay_color: "#dddddd"
  # overlay_filter: "0"
  overlay_image: "/assets/splash/template.jpg"
excerpt: "Sharing problems is the best way to solve them."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: /assets/splash/feat1-1.jpg
    title: "The best post"
    excerpt: "Sample text 1 with **markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/splash/feat1-2.jpg
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/splash/feat1-3.jpg
    title: "Next Posts"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/next"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}

