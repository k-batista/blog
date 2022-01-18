---
title: "Hello, @World!"
layout: splash
permalink: /
header:
  overlay_color: "#dddddd"
  overlay_filter: "0"
# excerpt: "Sharing problems is the best way to solve them."
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

