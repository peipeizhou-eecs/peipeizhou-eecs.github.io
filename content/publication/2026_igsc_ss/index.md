---
title: "To Overlay or to Customize? Revisiting Architectural Choices in Heterogeneous Systems (🔥📣New Paper & Project🔥📣! )"
publication_types:
  - "1"
authors:
  - Xingzhen Chen
  - Shixin Ji
  - Zheng Dong 
  - admin
publication: Proceedings of the ACM International Green and Sustainable Computing Conference 2026, IGSC ’26, June 22 - June 24, 2026, Canandaigua, NY, USA. Full Paper Accepted!  

abstract: >-
  Autonomous Driving Systems (ADS) increasingly rely on diverse deep neural networks to support perception, prediction, planning, and control under strict real-time constraints. FPGA-based heterogeneous computing provides an attractive platform for DNN workloads, but it raises a fundamental deployment question: should the system rely on a flexible overlay architecture, or repeatedly load customized bitstreams optimized for dedicated models, which should be treated as a first-class systems problem rather than a purely architectural one? Overlay-based execution offers fast model switching and better adaptability relying on lightweight instruction or parameter updates, while customized architectures can provide higher model-wise efficiency at the cost of reconfiguration latency and reduced flexibility. However, the boundary between these two design choices remains unclear in realistic ADS scenarios.

  In this work, we present a systematic study of this trade-off from a deployment-centric perspective, focusing on an autonomous driving scenario. Instead of treating overlay and customized acceleration as isolated design points, we analyze when each approach is preferable under practical conditions, including workload variation, architectural design, reconfiguration latency, and switching frequency. Our analysis shows that overlay-based architecture is more suitable for highly frequent model switching under the state-of-the-art architecture. However, as bitstream reload overhead continues to reduce, customized architectures may become increasingly attractive, especially for workloads with efficiency requirements. Conversely, if overlay architectures become more capable and flexible, they may further expand their advantage over customized architectures. These observations provide design insights for future architectural design, and the optimal deployment strategy will be flipped according to the technique development.


draft: false
featured: true
links:
#- name: arXiv
#  url: https://arxiv.org/abs/2604.07523 
- name: PDF
  url:  https://dl.acm.org/doi/10.1145/3797248.3816189
#- name: Code
#  url: https://github.com/arc-research-lab/AGILE
- name: Slides
  url: "20260712_IGSC26_Overlay_Final_ShareVersion.pdf"
#- icon: youtube
#  icon_pack: fab
#  name: Video
#  url: https://youtu.be/P7PLsBpphg0 
tags:
  - IGSC 
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2026-06-22T00:53:11.299Z
---
