---
title: "ARIES: An Agile MLIR-Based Compilation Flow for Reconfigurable Devices with AI Engines(🔥📣 FPGA 2025 Best Paper Candidate🔥📣! )"
publication_types:
  - "1"
authors:
  - Jinming Zhuang
  - Shaojie Xiang 
  - Hongzheng Chen
  - Niansong Zhang
  - Zhuoping Yang
  - Tony Mao
  - Zhiru Zhang
  - admin
publication: Proceedings of the 2025 ACM/SIGDA International Symposium on Field Programmable Gate Arrays, FPGA 2025, Feb. 28 - March 3, Monterey, CA, US. Full Paper Accepted! https://dl.acm.org/doi/10.1145/3706628.3708870 


abstract: >-
  As AI continues to grow, modern applications are becoming more data- and compute-intensive, driving the development of specialized AI chips to meet these demands. One example is AMD's AI Engine (AIE), a dedicated hardware system that includes a 2D array of high-frequency very-long instruction words (VLIW) vector processors to provide high computational throughput and reconfigurability. However, AIE's specialized architecture presents tremendous challenges in programming and compiler optimization. Existing AIE programming frameworks lack a clean abstraction to represent multi-level parallelism in AIE; programmers have to figure out the parallelism within a kernel, manually do the partition, and assign sub-tasks to different AIE cores to exploit parallelism. These significantly lower the programming productivity. Furthermore, some AIE architectures include FPGAs to provide extra flexibility, but there is no unified intermediate representation (IR) that captures these architectural differences. As a result, existing compilers can only optimize the AIE portions of the code, overlooking potential FPGA bottlenecks and leading to suboptimal performance. 


  To address these limitations, we introduce ARIES, an agile multilevel intermediate representation (MLIR) based compilation flow for reconfigurable devices with AIEs. ARIES introduces a novel programming model that allows users to map kernels to separate AIE cores, exploiting task- and tile-level parallelism without restructuring code. It also includes a declarative scheduling interface to explore instruction-level parallelism within each core. At the IR level, we propose a unified MLIR-based representation for AIE architectures, both with or without FPGA, facilitating holistic optimization and better portability across AIE device families. For the General Matrix Multiply (GEMM) benchmark, ARIES achieves 4.92 TFLOPS, 15.86 TOPS, and 45.94 TOPS throughput under FP32, INT16, and, INT8 data types on Versal VCK190 respectively. Compared with the state-of-the-art (SOTA) work CHARM for AIE, ARIES improves the throughput by 1.17x, 1.59x, and 1.47x correspondingly. For ResNet residual layer, ARIES achieves up to 22.58x speedup compared with optimized SOTA work Riallto on Ryzen-AI NPU. ARIES is opensourced on GitHub: https://github.com/arc-research-lab/Aries.

draft: false
featured: true
links:
- name: PDF
  url: https://dl.acm.org/doi/pdf/10.1145/3706628.3708870 
- name: Code
  url: https://github.com/arc-research-lab/Aries
- name: Slides
  url: "FPGA25_ARIES_Slides_ShareVersion.pdf"

tags:
  - FPGA 
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2025-01-10T00:53:11.299Z
---
