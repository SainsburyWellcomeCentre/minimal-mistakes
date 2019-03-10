---
permalink: /visualisation/
title: "Visualising Data"
layout: splash
excerpt: "MATLAB and Python tools for visualising raw data"
toc: false
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/acquisition/rgb_brain_banner.jpg
  actions:
    - label: "All repos"
      url: "https://github.com/orgs/SainsburyWellcomeCentre/teams/serial2p/repositories"

feature_row_lasagna:
  - image_path: /assets/images/home/Lasagna.jpg
    url: "https://github.com/SainsburyWellcomeCentre/lasagna"
    alt: "Lasagna"
    title: "Visualisation: Lasagna"
    excerpt: "Slicing visualisation in Python"
    btn_label: "Repo"
    btn_class: "btn--primary"

feature_row_masiv:
  - image_path:  /assets/images/home/masiv.jpg
    alt: "MaSIV"
    title: "Visualisation: MaSIV"
    excerpt: "Incremental loader for full-res data in MATLAB"
    url: "https://github.com/alexanderbrown/masiv"
    btn_label: "Repo"
    btn_class: "btn--primary"

---

{% include feature_row id="feature_row_lasagna" type="left" %}
{% include feature_row id="feature_row_masiv"      type="left" %}
