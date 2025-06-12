---
title: "OHA R Packages"
excerpt: "Suite of open-source R packages for global health analytics."
header:
  #image: /assets/images/portfolio/oha_packages.png
  teaser: /assets/images/portfolio/oha_packages.png
sidebar:
  - title: "Role"
    image: /assets/images/portfolio/si_logo.png
    text: "Developer, Maintainer"
  - title: "Timeline"
    text: "2021-2025"
  - title: "Custom R Packages"
    text: "[rOpenSci](https://usaid-oha-si.r-universe.dev/packages)"
  - title: "Tools"
    text: "R, Git, SQL"  
layout: single
collection: portfolio
classes: wide
date: 2025-06-10
tags: ['Tooling', 'Open Source', 'R']
---

As part of the data science team at USAID’s Office of HIV/AIDS (OHA), I contributed to the development and maintenance of a suite of open-source R packages designed to support global health analytics with PEPFAR data. These packages were built to enhance efficiency, support reproducible workflows, and foster a more collaborative data environment across internal and country-based teams.

Together, our packages form the core infrastructure used by data scientists and analysts within OHA. Each tool serves a specific purpose — from importing and reshaping structured program data to standardizing visualizations and managing secure API authentication. Highlights include:

-   [mindthegap](https://usaid-oha-si.github.io/mindthegap/) – access and tidy tools for working with UNAIDS epidemiological estimates

-   [tameDP](https://usaid-oha-si.github.io/tameDP/) – reshapes the PEPFAR Target Setting Tool (TST) for analytic use

-   [gophr](https://usaid-oha-si.github.io/gophr/) – utilities for importing and processing PEPFAR structured datasets (PSDs)

-   [glamr](https://usaid-oha-si.github.io/glamr/) – workflow enhancements, environment setup, and authentication support

-   [glitr](https://usaid-oha-si.github.io/glitr/) – consistent ggplot2-based theming and colors for data visualizations

-   [cascade](https://usaid-oha-si.github.io/cascade/) - automatically generate clinical cascade and PEPFAR indicator plots

-   [grabr](https://usaid-oha-si.github.io/grabr/) – additional utilities with a focus on API integration and automation

-   [gagglr](https://usaid-oha-si.github.io/gagglr/) – checks for package versioning consistency across the suite

-   [themask](https://usaid-oha-si.github.io/themask/) – generates masked, shareable datasets that mimic real PEPFAR structures

We built out automated documentation sites, implemented GitHub Actions for CI/CD, and used GitHub Issues to manage development and feedback loops. Several packages are published via our rOpenSci R-universe, with a focus on usability, modularity, and institutional sustainability.

This infrastructure has enabled faster onboarding, increased reproducibility, and higher consistency in reporting and analysis across our programs.
