---
title: "Open Serial Section"
layout: splash
permalink: /
date: 2019-03-07
header:
  overlay_image: /assets/images/home/GCamp6s_brain.jpg
  actions:
    - label: "All repos"
      url: "https://github.com/orgs/SainsburyWellcomeCentre/teams/serial2p/repositories"
excerpt: "Open-source Serial Section Imaging"
intro:
  - excerpt: "Acquisition, analysis, and hardware hacks for open source serial section imaging"
feature_row_01:
  - image_path: "https://raw.githubusercontent.com/wiki/BaselLaserMouse/StitchIt/images/rgb_brain_example.jpg"
    alt: "Acquisition"
    title: "Acquisition"
    excerpt: "MATLAB-based acquisition software: ready to install and ready to modify"
    url: "https://github.com/SainsburyWellcomeCentre/BakingTray/wiki"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/home/stitching.jpg
    alt: "Stitching raw data"
    title: "Stitching"
    excerpt: "Modular tile stitcher: compatible with any acquisition hardware."
    url: "https://github.com/SainsburyWellcomeCentre/StitchIt"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/home/Registration.jpg
    alt: "registatrion"
    title: "Registration to Allen Atlas"
    excerpt: "Register brains to the Allen Atlas with Elastix or Nifty"
    url: /registration
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row_02:
  - image_path: "http://mouse.vision/images/research/board_equations_256.jpg"
    alt: "Nifty Registration"
    title: "Nifty-based registration"
    excerpt: "Register brains to the Allen Atlas with Nifty"
    url: "https://github.com/SainsburyWellcomeCentre/aMAP/wiki"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: "http://mouse.vision/images/research/board_equations_256.jpg"
    title: "Visualisation: Lasagna"
    excerpt: "Slicing visualisation in Python"
    url: "https://github.com/SainsburyWellcomeCentre/lasagna"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: "http://mouse.vision/images/research/board_equations_256.jpg"
    alt: "hacks"
    title: "Hacks"
    excerpt: "Hardware hacks for your serial-section 2p"
    url: "https://github.com/SainsburyWellcomeCentre/TissueVisionMods/wiki"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row_01" %}

{% include feature_row id="feature_row_02" %}
