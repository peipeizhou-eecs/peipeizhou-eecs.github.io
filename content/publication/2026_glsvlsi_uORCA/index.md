---
title: "μ-ORCA: Optimizing Acceleration for Microsecond-Scale Deep Neural Network Inference on ACAP (🔥📣New Paper & Project🔥📣! )"
publication_types:
  - "1"
authors:
  - Shixin Ji
  - Jinming Zhuang
  - Zhuoping Yang
  - Xingzhen Chen
  - Wei Zhang 
  - admin
publication: Proceedings of the ACM Great Lakes Symposium on VLSI 2026, GLSVLSI ’26, June 22 - June 24, 2026, Canandaigua, NY, USA. Full Paper Accepted!  

abstract: >-
  Heterogeneous reconfigurable platforms with tensor cores, suchas AMD ACAP, are increasingly adopted for deep neural network(DNN) inference due to their high throughput and flexibility. How-ever, their suitability for microsecond-scale inference on small prob-lem sizes remains underexplored. In jet-tagging applications inhigh-energy physics, inefficient on-chip communication and largeinter-layer latency prevent existing frameworks from meeting the1-𝜇s latency budget. Moreover, hardware overheads such as syn-chronization and VLIW processor prologue are often overlooked,making it infeasible to optimize accelerators correctly. To addressthese problems, we propose µ-ORCA, a customized heterogeneousaccelerator framework for ultra-low-latency model inference. µ-ORCA enables direct inter-layer communication between DNN lay-ers on the AIE array, instead of using shared memory tiles or FPGAfabric. Moreover, a 512-bit/cycle cascade connection is applied in-stead of a 32-bit/cycle DMA connection. µ-ORCA also provides anoverhead-aware performance model that adapts to different NNlayer sizes, and conducts design space exploration to optimize end-to-end latency. µ-ORCA supports MLP and DeepSets models withnon-MM kernels, including bias, ReLU, and global aggregation onAIE. We evaluate µ-ORCA on the AMD ACAP VEK280 platform.Experimental results show that µ-ORCA achieves average latencyreduction of >1.70× and >1.83× compared with different state-of-the-art ACAP frameworks, and achieves 0.93 𝜇s latency for a 6-layerreal-world DeepSets model, satisfying the latency budget. We opensource µ-ORCA at https://github.com/arc-research-lab/u-ORCA.

draft: false
featured: true
links:
#- name: arXiv
#  url: https://arxiv.org/abs/2604.07523 
- name: PDF
  url: https://dl.acm.org/doi/10.1145/3787109.3815309 
#- name: Code
#  url: https://github.com/arc-research-lab/AGILE
- name: Slides
  url: "20260712_GLSVLSI26_uORCA_Final_ShareVersion.pdf"
- icon: youtube
  icon_pack: fab
  name: Video
  url: https://youtu.be/kenDH_976ng 
tags:
  - GLSVLSI 
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2026-06-22T00:53:11.299Z
---
