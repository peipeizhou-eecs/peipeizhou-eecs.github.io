---
title: "AGILE: Lightweight and Efficient Asynchronous GPU-SSD Integration(🔥📣New Paper & Project🔥📣! )"
publication_types:
  - "1"
authors:
  - Zhuoping Yang
  - Jinming Zhuang
  - Xingzhen Chen
  - Alex Jones
  - admin
publication: Proceedings of the International Conference for High Performance Computing, Networking, Storage, and Analysis, SC 2025, Nov. 16 - Nov. 21, 2025, St. Louis, MO, US. Full Paper Accepted! https://dl.acm.org/doi/10.1145/3712285.3759778 

abstract: >-
  Graphics Processing Units (GPUs) have become essential for com- putationally intensive applications. However, emerging workloads such as recommender systems, graph analytics, and data analytics often involve processing data exceeding GPU device memory capacity. To mitigate this issue, existing solutions enable GPUs to use CPU DRAM or SSDs as external memory. Among them, the GPU-centric approach lets GPU threads directly initiate NVMe requests, eliminating CPU intervention overhead over traditional methods. However, the SOTA GPU-centric approach adopts a synchronous IO model, and threads must tolerate the long latency in communication before starting any tasks. 


  In this work, we propose AGILE, a lightweight and efficient asynchronous library allowing GPU threads to access SSDs asynchronously while eliminating deadlock risks. AGILE also integrates a flexible software cache using GPU High-Bandwidth Memory (HBM). We demonstrate that the asynchronous GPU-centric IO achieves up to 1.88× improvement in workloads with different computation-to-communication (CTC) ratios. We also compare AGILE with the SOTA work BaM on Deep Learning Recommendation Models (DLRM) with various settings, and the results show that AGILE achieves 1.75× performance improvement due to its efficient design and the overlapping strategy enabled by an asynchronous IO model. We further evaluate AGILE’s API overhead on graph applications, and the results demonstrate AGILE reduces software cache overhead by up to 3.12× and overhead in NVMe IO requests by up to 2.85×. Compared with BaM, AGILE consumes fewer registers and exhibits up to 1.32× reduction in the usage of registers.

draft: false
featured: true
links:
#- name: arXiv
#  url: https://arxiv.org/abs/2504.19365
- name: PDF
  url: https://dl.acm.org/doi/10.1145/3712285.3759778 
- name: Code
  url: https://github.com/arc-research-lab/AGILE
- name: Slides
  url: "20251119_SC25_AGILE_Final_ShareVersion.pdf"
- name: Video
  url: https://youtube.com/watch?v=RN2XhpcKSO4&feature=youtu.be
tags:
  - Supercomputing 
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2025-11-29T00:53:11.299Z
---
