---
layout: collection
title: "Surf collection"
collection: surf
permalink: /surf-collection/
author_profile: true

entries_layout: list #grid
classes: wide

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/campervan/everything-butter-view-1.png
  actions:
    - label: "Learn More"
      url: "/furniture/more/"
  caption: "Photo credit: [**Cameron?**](https://d-i-ply.com/)"
excerpt: "Are you a designer interested in having your ideas made real?
Want to make a passive income?
Submit your design here and get started.."
intro: 
  - excerpt: 'Add your design into our product range and other people will get the opportunity to build and own YOUR design. Not only that, you will get an attractive fee for each of your designs sold!'

# aligned left
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.png
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "details"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row:
    #1 - chair
  - image_path: /assets/images/furniture/chair.png
    image_caption: "Image courtesy of [Chair](https://d-i-ply.com/)"
    alt: "P9 Chair - Alejandro Palandjoglou"
    title: "P9 Chair"
    excerpt: "Designed by renowned Argentinean industrial designer Alejandro Palandjoglou, the P9 chair series combines form with function."
    url: "furniture/p9-chair"
    btn_label: "Read More"
    btn_class: "btn--primary"
    #2 - table
  - image_path: /assets/images/furniture/table.png
    alt: "Wave table"
    title: "Wave table"
    excerpt: "This is some content about wave table."
    url: "vawe-table"
    btn_label: "Read More"
    btn_class: "btn--primary"
    #3 - lamp
  - image_path: /assets/images/furniture/lamp.png
    title: "Parametric Lamp"
    alt: "Parametric Lamp"
    excerpt: "This is some content about Parametric lamp."
    url: "furniture/parametric-lamp"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}