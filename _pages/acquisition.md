---
permalink: /acquisition/
title: "Registering serial section data"
layout: splash
excerpt: "Sample registration to the Allen Atlas"
toc: false
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/registration/reg_banner.jpg
  actions:
    - label: "All repos"
      url: "https://github.com/orgs/SainsburyWellcomeCentre/teams/serial2p/repositories"

feature_row_bakingtray:
  - image_path: "https://raw.githubusercontent.com/wiki/BaselLaserMouse/StitchIt/images/rgb_brain_example.jpg"
    url: "https://github.com/SainsburyWellcomeCentre/BakingTray/wiki"
    alt: "Acquisition"
    title: "BakingTray: serial-section acquisition software"
    excerpt: 'BakingTray is modular serial-section acquisition software for MATLAB. It can easily be modified to utilise any desired acquisition hardware (scanners, stages, etc). Images are currently acquired with [ScanImage](https://vidriotechnologies.com/), but BakingTray can easily be extended to work with any acquisition system (e.g. a spinning-disk confocal or your own scanning software).'
    btn_label: "Repo"
    btn_class: "btn--primary"

feature_row_stitchit
  - image_path:  /assets/images/home/stitching.jpg
    alt: "Stitching
    title: "StitchIt: assembling tile scan data to stitched sections"
    excerpt: "Pre-processes data during acquisition, streams the last stitched section to a web page, initiates stitching automatically when acquisition completes. Includes tools for downsampling and generally batch-processing image stacks. Operations highly parallelised for speed."
    url: "https://github.com/SainsburyWellcomeCentre/StitchIt"
    btn_label: "Repo"
    btn_class: "btn--primary"

---

{% include feature_row id="feature_row_bakingtray" type="left" %}
{% include feature_row id="feature_row_stitchit"   type="left" %}
