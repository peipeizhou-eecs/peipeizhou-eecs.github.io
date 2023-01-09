---
title: "CHARM: Composing Heterogeneous AcceleRators for Matrix Multiply on
  Versal ACAP Architecture (🔥📣New Paper & Project🔥📣! )"
publication_types:
  - "1"
authors:
  - Jinming Zhuang
  - Jason Lau
  - Hanchen Ye
  - Zhuoping Yang
  - Yubo Du
  - Jack Lo
  - Kristof Denolf
  - Stephen Neuendorffer
  - Alex K. Jones
  - Jingtong Hu
  - Deming Chen
  - Jason Cong
  - admin
publication: 2023 ACM/SIGDA International Symposium on Field Programmable Gate Arrays (FPGA 23)
abstract: > 
Dense matrix multiply (MM) serves as one of the most heavily used kernels in deep learning applications. To cope with the high computation demands of these applications, heterogeneous architectures featuring both FPGA and dedicated ASIC accelerators have emerged as promising platforms. For example, the AMD/Xilinx Versal ACAP architecture combines general-purpose CPU cores and programmable logic (PL) with AI Engine processors (AIE) optimized for AI/ML.  An array of 400 AI Engine processors executing at 1 GHz can theoretically provide up to 6.4 TFLOPs performance for 32-bit floating-point (fp32) data. However, machine learning models often contain both large and small MM operations.  While large MM operations can be parallelized efficiently across many cores, small MM operations typically cannot. In our investigation, we observe that executing some small MM layers from the BERT natural language processing model on a large, monolithic MM accelerator in Versal ACAP achieved less than 5% of the theoretical peak performance. Therefore, one key question arises: How can we design accelerators to fully use the abundant computation resources under limited communication bandwidth for end-to-end applications with multiple MM layers of diverse sizes?

draft: false
featured: true
links:
- name: Code 
  url: https://github.com/arc-research-lab/CHARM 
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2023-01-01T00:53:11.299Z
---
