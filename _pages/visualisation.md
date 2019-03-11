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
    excerpt: "This Python-based software is currently under development. It provides three linked orthogonal 2-D views for fast visualisation of downsampled image stacks. Allows overlays of multiple brains, multiple channels, traced neurites, or soma locations. Includes viewer for Allen Atlas. Extendable via plugins."
    btn_label: "Repo"
    btn_class: "btn--primary"

feature_row_masiv:
  - image_path:  /assets/images/home/masiv.jpg
    alt: "MaSIV"
    title: "Visualisation: MaSIV"
    excerpt: "This MATLAB-based package loads a downsampled image stacks but presents the user with full-res data as they zoom in. MaSIV is stable but can only display a single channel at once. Extendable via plugins."
    url: "https://github.com/alexanderbrown/masiv"
    btn_label: "Repo"
    btn_class: "btn--primary"

---

{% include feature_row id="feature_row_masiv"   type="left" %}
{% include feature_row id="feature_row_lasagna" type="left" %}

