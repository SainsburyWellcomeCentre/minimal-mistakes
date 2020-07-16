---
permalink: /registration/
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

feature_row_ara_tools:
  - image_path: /assets/images/registration/reg_coronal.jpg
    url: "https://github.com/SainsburyWellcomeCentre/ara_tools"
    alt: "MATLAB based registration"
    title: "Elastix-based registration"
    excerpt: 'Registering images in MATLAB using Elastix'
    btn_label: "Repo"
    btn_class: "btn--primary"

feature_row_amap:
  - image_path:  /assets/images/registration/NiftyReg_Logo.jpg
    alt: "NiftyReg Registration"
    title: "NiftyReg-based registration"
    excerpt: "Register brains using NiftyReg via aMAP-Python"
    url: "https://github.com/SainsburyWellcomeCentre/amap-python"
    btn_label: "Repo"
    btn_class: "btn--primary"

---

{% include feature_row id="feature_row_ara_tools" type="left" %}
{% include feature_row id="feature_row_amap"      type="left" %}

## Related tools
- [ClearMap](https://idisco.info/) - An Elastix/Python pipeline related to iDISCO
- [SimpleElastix](https://simpleelastix.github.io/) - A nice Elastix wrapper for multiple languages
- [BIRDS (pre-print)](https://www.biorxiv.org/content/10.1101/2020.06.30.181255v2)
- [Geometry Processing of Conventionally Produced Mouse Brain Slice Images](https://www.ics.uci.edu/~agarwal/mouseBrain/index.html)
- [Whole Brain Software](http://www.wholebrainsoftware.org/)
- [MelastiX](https://github.com/raacampbell/matlab_elastix) - Elastix wrapper for MATLAB. 
