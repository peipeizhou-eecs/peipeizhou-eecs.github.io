---
title: "DORA: Dataflow-Instruction Orchestration Architecture for DNN Acceleration (🔥📣New Paper & Project🔥📣! )"
publication_types:
  - "1"
authors:
  - Xingzhen Chen
  - Zhuoping Yang
  - Jinming Zhuang
  - Shixin Ji
  - Sarah Schultz
  - Zheng Dong
  - Weisong Shi 
  - admin
publication: Proceedings of the ACM Great Lakes Symposium on VLSI 2026, GLSVLSI ’26, June 22 - June 24, 2026, Canandaigua, NY, USA. Full Paper Accepted!  

abstract: >-
  As deep neural networks develop significantly more diverse andcomplex, achieving high performance and efficiency on complicatedDNN models faces pressing challenges. Modern DNN workloadsare increasingly diverse in operation types, tensor shapes, andexecution dependencies, making it difficult to sustain high hardwareefficiency across models. In addition, a generic accelerator oftenincurs substantial overhead when executing diverse workloads.

  To address these problems, we propose DORA, an instruction-based overlay architecture that explicitly describes dataflow viaa proposed ISA, enabling fine-grained control of data movement,computation, and synchronization at the layer level. To supportflexibility while achieving high performance, DORA adopts a novelon-chip memory management and computation parallelism man-agement mechanism. DORA proposes a compilation frameworkthat can generate instructions for given DNN workloads after atwo-stage design space exploration. DORA framework also incorpo-rates a MILP-based and a heuristic-based search engine to generatethe schedule solution for different needs and constraints.

  We prototype DORA on the AMD Versal VCK190 platform,demonstrating its deployability on existing reconfigurable systems.Experimental results show that DORA maintains stable efficiency,with less than 5% variation on a single vector processor acrossworkloads exhibiting up to 6× variation in operation counts. Com-pared to state-of-the-art accelerators, DORA consistently achieveshigher performance, delivering up to 5× throughput improvement.The heuristic-based scheduler further achieves up to 90% opti-mality under practical time constraints. DORA is open-sourcedat https://github.com/arc-research-lab/DORA.git.

draft: false
featured: true
links:
#- name: arXiv
#  url: https://arxiv.org/abs/2604.07523 
- name: PDF
  url: https://dl.acm.org/doi/10.1145/3787109.3815288 
#- name: Code
#  url: https://github.com/arc-research-lab/AGILE
#- name: Slides
#  url: "20251119_SC25_AGILE_Final_ShareVersion.pdf"
#- icon: youtube
#  icon_pack: fab
#  name: Video
#  url: https://youtube.com/watch?v=RN2XhpcKSO4&feature=youtu.be
tags:
  - GLSVLSI 
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2026-06-22T00:53:11.299Z
---
