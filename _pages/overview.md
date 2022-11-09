---
title: "Überblick"
layout: splash
permalink: /overview/
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/lines/grundstuecke.png
  caption: "Projektüberblick"
excerpt: "Verschaffen Sie sich einen Überblick."

feature_north:
  - image_path: /assets/images/lines/schnitt_nord.png
    alt: "Hausschnitt Nord"
    title: "Nord"

feature_south:
  - image_path: /assets/images/lines/schnitt_sued.png
    alt: "Hausschnitt Süd"
    title: "Süd"

feature_east:
  - image_path: /assets/images/lines/schnitt_ost.png
    alt: "Hausschnitt Ost"
    title: "Ost"

feature_west:
  - image_path: /assets/images/lines/schnitt_west.png
    alt: "Hausschnitt West"
    title: "West"

feature_row1:
  - image_path: /assets/images/lines/grundstuecke.png
    alt: "Grundstücke"
    excerpt: ""
    url: "/assets/images/lines/grundstuecke.png"
    btn_label: "Vergrößern"
    btn_class: ""

feature_row2:
  - image_path: /assets/images/visual_221013_01_s.jpg
    alt: "Hausansicht Südost"
    title: "Südost"
    excerpt: ''

feature_row3:
  - image_path: /assets/images/visual_221013_02_s.jpg
    alt: "Hausansicht Südwest"
    title: "Südwest"
    excerpt: ''

feature_row4:
  - image_path: /assets/images/visual_221013_04_s.jpg
    alt: "Hausansicht Nordost"
    title: "Nordost"

feature_row5:
  - image_path: /assets/images/visual_221013_05_s.jpg
    alt: "Hausansicht Nordwest"
    title: "Nordwest"

---

{% include feature_row id="intro" type="center" %}

<h1 style="text-align:center">Hausschnitte</h1>

---

{% include feature_row id="feature_south" type="center" %}
{% include feature_row id="feature_north" type="center" %}

{% include feature_row id="feature_east" type="center" %}
{% include feature_row id="feature_west" type="center" %}

<h1 style="text-align:center">Grundstücke</h1>

{% include feature_row id="feature_row1" type="center" %}

<h1 style="text-align:center">Ansichten</h1>

{% include feature_row id="feature_row2" type="center" %}

{% include feature_row id="feature_row3" type="center" %}

{% include feature_row id="feature_row4" type="center" %}

{% include feature_row id="feature_row5" type="center" %}
