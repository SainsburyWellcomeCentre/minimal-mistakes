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
  - excerpt: "Acquisition, analysis, and visualisation of serial-section imaging data."
feature_row_01:
  - image_path: /assets/images/home/waterbathInScope.jpg
    alt: "Acquisition"
    title: "Acquisition"
    excerpt: "MATLAB-based acquisition and stitching software: ready to install and ready to modify."
    url: /acquisition
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/home/Registration.jpg
    alt: "registatrion"
    title: "Registration to Allen Atlas"
    excerpt: "Register brains to the Allen Atlas with Elastix or NiftyReg."
    url: /registration
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row_02:
  - image_path: /assets/images/home/Lasagna.jpg
    title: "Visualisation: Lasagna"
    excerpt: "Slicing visualisation in Python"
    url: "https://github.com/SainsburyWellcomeCentre/lasagna"
    btn_label: "Repo"
    btn_class: "btn--primary"
  - image_path: /assets/images/home/masiv.jpg
    title: "Visualisation: MaSIV"
    excerpt: "Incremental loader for full-res data in MATLAB"
    url: "https://github.com/alexanderbrown/masiv"
    btn_label: "Repo"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row id="feature_row_01"      %}
{% include feature_row id="feature_row_02"      %}
