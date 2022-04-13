---
title: "Überblick"
layout: splash
permalink: /overview/
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/lines/grundstuecke.png
  caption: "Projektüberblick"
excerpt: "Verschaffen Sie sich einen Überblick über das Projekt und die Bebauungsplanung."
feature_row:
  - image_path: /assets/images/lines/gelaendeschnitt_a.png
    alt: "Geländeschnitt A"
    title: "Geländeschnitt A"
    excerpt: "..."
    url: "/assets/images/lines/gelaendeschnitt_a.png"
    btn_label: "Vergrößern"
    btn_class: "btn--primary"
  - image_path: /assets/images/lines/gelaendeschnitt_b.png
    alt: "Geländeschnitt B"
    title: "Geländeschnitt B"
    excerpt: "..."
    url: "/assets/images/lines/gelaendeschnitt_b.png"
    btn_label: "Vergrößern"
    btn_class: "btn--primary"
  - image_path: /assets/images/lines/gelaendeschnitt_c.png
    alt: "Geländeschnitt C"
    title: "Geländeschnitt C"
    excerpt: "..."
    url: "/assets/images/lines/gelaendeschnitt_c.png"
    btn_label: "Vergrößern"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/visual_2.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/visual_2.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/visual_2.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
