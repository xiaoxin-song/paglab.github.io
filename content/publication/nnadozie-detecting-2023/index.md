---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Detecting Cassava Plants under Different Field Conditions Using UAV-Based RGB
  Images and Deep Learning Models
subtitle: ''
summary: ''
authors:
- Emmanuel C. Nnadozie
- Ogechukwu N. Iloanusi
- Ozoemena A. Ani
- Kang Yu
tags:
- object detection
- precision agriculture
- computer vision
- deep learning
- YOLOv5
- crop counting
- plant detection
categories: []
date: '2023-01-01'
lastmod: 2025-05-07T21:24:35+02:00
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
publishDate: '2025-05-07T19:24:35.422506Z'
publication_types:
- '2'
abstract: A significant number of object detection models have been researched for
  use in plant detection. However, deployment and evaluation of the models for real-time
  detection as well as for crop counting under varying real field conditions is lacking.
  In this work, two versions of a state-of-the-art object detection model—YOLOv5n
  and YOLOv5s—were deployed and evaluated for cassava detection. We compared the performance
  of the models when trained with different input image resolutions, images of different
  growth stages, weed interference, and illumination conditions. The models were deployed
  on an NVIDIA Jetson AGX Orin embedded GPU in order to observe the real-time performance
  of the models. Results of a use case in a farm field showed that YOLOv5s yielded
  the best accuracy whereas YOLOv5n had the best inference speed in detecting cassava
  plants. YOLOv5s allowed for more precise crop counting, compared to the YOLOv5n
  which mis-detected cassava plants. YOLOv5s performed better under weed interference
  at the cost of a low speed. The findings of this work may serve to as a reference
  for making a choice of which model fits an intended real-life plant detection application,
  taking into consideration the need for a trade-off between of detection speed, detection
  accuracy, and memory usage.
publication: '*Remote Sensing*'
doi: 10.3390/rs15092322
links:
- name: URL
  url: https://www.mdpi.com/2072-4292/15/9/2322
---
