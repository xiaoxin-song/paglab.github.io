---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Mapping Plant Nitrogen Concentration and Aboveground Biomass of Potato Crops
  from Sentinel-2 Data Using Ensemble Learning Models
subtitle: ''
summary: ''
authors:
- Hang Yin
- Fei Li
- Haibo Yang
- Yunfei Di
- Yuncai Hu
- Kang Yu
tags:
- potato
- plant nitrogen concentration
- feature selection
- spectral indices
- Sentinel-2 imagery
- ensemble learning model
categories: []
date: '2024-01-01'
lastmod: 2025-05-07T21:24:36+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2025-05-07T19:24:36.112193Z'
publication_types:
- '2'
abstract: Excessive nitrogen (N) fertilization poses environmental risks at regional
  and global levels. Satellite remote sensing provides a novel approach for large-scale
  N monitoring. In this study, we evaluated the performance of different types of
  spectral bands and indices (SIs) coupled with ensemble learning models (ELMs) at
  retrieving the plant N concentration (PNC) and plant aboveground biomass (AGB) of
  potato from Sentinel-2 images. Cloud-free Sentinel-2 imagery was acquired during
  the tuber-formation to starch-accumulation stages from 2020 to 2021. Fourteen optimal
  SIs were selected using the successive projections algorithm (SPA) and principal
  component analysis (PCA). The PNC and AGB estimation models were then built using
  an ELMs. The results showed that the SIs based on chlorophyll absorption bands were
  strongly related to potato PNC and AGB. Also, the N-correlated bands were mainly
  concentrated in the red-edge (705 nm) and short-wave infrared (1610 and 2190 nm)
  regions. The ELMs successfully predicted PNC and AGB (R2PNC = 0.74; R2AGB = 0.82).
  Compared with the other five base models (k-nearest neighbor (KNN), partial least
  squares regression (PLSR), support vector regression (SVR), random forest (RF),
  and Gaussian process regression (GPR)), the ELMs provided higher PNC and AGB estimation
  accuracy and effectively reduced overfitting to training data. This study demonstrated
  that the promising solution of using SPA-PCA coupled with an ensemble learning model
  improves the estimation accuracy of potato PNC and AGB based on Sentinel-2 imagery
  data.
publication: '*Remote Sensing*'
doi: 10.3390/rs16020349
links:
- name: URL
  url: https://www.mdpi.com/2072-4292/16/2/349
---
