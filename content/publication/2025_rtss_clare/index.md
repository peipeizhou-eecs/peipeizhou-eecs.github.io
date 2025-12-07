---
title: "DERCA: DetERministic Cycle-Level Accelerator on Reconfigurable Platforms in DNN-Enabled Real-Time Safety-Critical Systems (🔥📣New Paper & Project🔥📣! )"
publication_types:
  - "1"
authors:
  - Shixin Ji 
  - Zhuoping Yang
  - Xingzhen Chen
  - Wei Zhang
  - Jinming Zhuang
  - Alex Jones
  - Zheng Dong
  - Admin
publication: To appear in the 46th IEEE Real-Time Systems Symposium, RTSS 2025, December 2–5, 2025, Boston, MA, USA. Full Paper Accepted!  

abstract: >-
  Deep neural network (DNN) models are increasingly deployed in real-time, safety-critical systems such as autonomous vehicles, driving the need for specialized AI accelerators. However, most existing accelerators support only non-preemptive execution or limited preemptive scheduling at the coarse granularity of DNN layers. This restriction leads to frequent priority inversion due to the scarcity of preemption points, resulting in unpredictable execution behavior and, ultimately, system failure. 

  To address these limitations and improve the real-time performance of AI accelerators, we propose DERCA, a novel accelerator architecture that supports fine-grained, intra-layer flexible preemptive scheduling with cycle-level determinism. DERCA incorporates an on-chip Earliest Deadline First (EDF) scheduler to reduce both scheduling latency and variance, along with a customized dataflow design that enables intra-layer preemption points (PPs) while minimizing the overhead associated with preemption. Leveraging the limited preemptive task model, we perform a comprehensive predictability analysis of DERCA, enabling formal schedulability analysis and optimized placement of preemption points within the constraints of limited preemptive scheduling. We implement DERCA on the AMD ACAP VCK190 reconfigurable platform. Experimental results show that DERCA outperforms state-of-the-art designs using non-preemptive and layer-wise preemptive dataflows, with less than 5% overhead in worst-case execution time (WCET) and only 6% additional resource utilization. DERCA is open-sourced on GitHub: https://github.com/arc-research-lab/DERCA.



draft: false
featured: true
links:
#- name: arXiv
#  url: https://arxiv.org/abs/2504.19365
#- name: PDF
#  url: https://dl.acm.org/doi/pdf/10.1145/3716368.3735215 
- name: Code
  url: https://github.com/arc-research-lab/DERCA
- name: Slides
  url: "20251205_DERCA_IEEE_RTSS_2025_ShareVersion.pdf"
tags:
  - RTSS 
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2025-12-05T00:53:11.299Z
---
