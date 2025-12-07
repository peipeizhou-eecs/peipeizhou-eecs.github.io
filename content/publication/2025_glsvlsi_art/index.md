---
title: "ART: Customizing Accelerators for DNN-Enabled Real-Time Safety-Critical Systems(🔥📣New Paper & Project🔥📣! )"
publication_types:
  - "1"
authors:
  - Shixin Ji
  - Xingzhen Chen
  - Jinming Zhuang
  - Zhuoping Yang
  - Sarah Schultz
  - Yukai Song
  - Jingtong Hu
  - Alex Jones
  - Zheng Dong
  - admin
publication: Proceedings of the Great Lakes Symposium on VLSI 2025, GLSVLSI 2025, June 30 - July 2, New Orleans, LA, US. Full Paper Accepted! https://dl.acm.org/doi/pdf/10.1145/3716368.3735215 

abstract: >-
  Real-time systems are widely applied in different areas like autonomous vehicles, where safety is the key metric. However, on the FPGA platform, most of the prior accelerator frameworks omit discussing the schedulability in such real-time safety-critical systems, leaving deadlines unmet, which can lead to catastrophic system failures. To address this, we propose the ART framework, a hardware-software co-design approach that transforms baseline accelerators into real-time guaranteed accelerators. On the software side, ART performs schedulability analysis and preemption point placement, optimizing task scheduling to meet deadlines and enhance throughput. On the hardware side, ART integrates the Global Earliest Deadline First (GEDF) scheduling algorithm, implements preemption, and conducts source code transformation to transform baseline HLS-based accelerators into designs targeted for real-time systems capable of saving and resuming tasks. ART also includes integration, debugging, and testing tools for full-system implementation. We demonstrate the methodology of ART on two kinds of popular accelerator models and evaluate on AMD Versal VCK190 platform, where ART meets schedulability requirements that baseline accelerators fail. ART is lightweight, utilizing <0.5% resources. With about 100 lines of user input, ART generates about 2.5k lines of accelerator code, making it a push-button solution.


draft: false
featured: true
links:
- name: PDF
  url: https://dl.acm.org/doi/pdf/10.1145/3716368.3735215 
#- name: Code
#  url: https://github.com/arc-research-lab/Aries
- name: Slides
  url: "ART_GLSVLSI25_ShareVersion.pdf"
tags:
  - GLSVLSI 
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2025-06-30T00:53:11.299Z
---
