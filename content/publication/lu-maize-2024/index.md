---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Maize plant detection using UAV-based RGB imaging and YOLOv5
subtitle: ''
summary: ''
authors:
- Chenghao Lu
- Emmanuel Nnadozie
- Moritz Paul Camenzind
- Yuncai Hu
- Kang Yu
tags: []
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
publishDate: '2025-05-07T19:24:36.378689Z'
publication_types:
- '2'
abstract: In recent years, computer vision (CV) has made enormous progress and is
  providing great possibilities in analyzing images for object detection, especially
  with the application of machine learning (ML). Unmanned Aerial Vehicle (UAV) based
  high-resolution images allow to apply CV and ML methods for the detection of plants
  or their organs of interest. Thus, this study presents a practical workflow based
  on the You Only Look Once version 5 (YOLOv5) and UAV images to detect maize plants
  for counting their numbers in contrasting development stages, including the application
  of a semi-auto-labeling method based on the Segment Anything Model (SAM) to reduce
  the burden of labeling. Results showed that the trained model achieved a mean average
  precision (mAP@0.5) of 0.828 and 0.863 for the 3-leaf stage and 7-leaf stage, respectively.
  YOLOv5 achieved the best performance under the conditions of overgrown weeds, leaf
  occlusion, and blurry images, suggesting that YOLOv5 plays a practical role in obtaining
  excellent performance under realistic field conditions. Furthermore, introducing
  image-rotation augmentation and low noise weight enhanced model accuracy, with an
  increase of 0.024 and 0.016 mAP@0.5, respectively, compared to the original model
  of the 3-leaf stage. This work provides a practical reference for applying lightweight
  ML and deep learning methods to UAV images for automated object detection and characterization
  of plant growth under realistic environments.
publication: '*Frontiers in Plant Science*'
doi: 10.3389/fpls.2023.1274813
links:
- name: URL
  url: https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2023.1274813
---
