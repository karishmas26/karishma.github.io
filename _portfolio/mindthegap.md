---
title: "mindthegap"
excerpt: "UNAIDS Data Accessibility"
header:
  #image: /assets/images/portfolio/mindthegap_epi-plot.png
  teaser: /assets/images/portfolio/mindthegap_epi-plot.png
sidebar:
  - title: "Role"
    image: /assets/images/portfolio/mindthegap_hex.png
    text: "Designer, Developer"
  - title: "Custom R Package"
    text: "[mindthegap](https://usaid-oha-si.github.io/mindthegap/)"
  - title: "Tools"
    text: "R, Git"  
gallery:
  - url: /assets/images/portfolio/mindthegap_epi-plot.png
    image_path: /assets/images/portfolio/mindthegap_epi-plot.png
    alt: "Kenya Epi Trends plot (1990-2024)"
  - url: /assets/images/portfolio/moz_95s.png
    image_path: /assets/images/portfolio/moz_95s.png
    alt: "Various Releases of the data hosted on GitHub"
layout: single 
collection: portfolio
date: 2025-06-10
tags: ['Package Development', 'R']
---

As one of the lead developers for `mindthegap`, our team developed an open-source R package to streamline the processing, tidying, and analysis of UNAIDS’s annual HIV country estimates data – estimates that are crucial for contextualizing epidemic control of HIV and targeting programmatic strategy. UNAIDS typically publishes these data as large, unstructured spreadsheets posing a recurring burden on teams working to extract, clean, and use them in applied analysis.

I led the effort to clean, standardize, and automate the processing of these datasets — munging raw files into a tidy format and adding useful variables for analysis within a PEPFAR context, such as goal metrics and PEPFAR affiliation. We also built a set of wrapper functions for quick, standardized visualizations, and hosted the processed data using GitHub Releases to allow lightweight, reliable access directly from R.

This project reduced redundancy and saved analysts hours of manual work each year, while reinforcing reproducibility and documentation standards. Our team also collaborated with UNAIDS to explore direct database access, and introduced unit tests, naming conventions, and scoped function design to improve long-term usability.

{% include gallery %}
