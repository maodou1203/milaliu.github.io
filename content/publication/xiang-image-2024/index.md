---
title: Image Manipulation Localization Using Dual-Shallow Feature Pyramid Fusion and
  Boundary Contextual Incoherence Enhancement
authors:
- Yan Xiang
- Xiaochen Yuan
- Kaiqi Zhao
- Tong Liu
- Zhiyao Xie
- Guoheng Huang
- Jianqing Li
date: '2024-01-01'
publishDate: '2025-12-15T15:16:09.181852Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Emerging Topics in Computational Intelligence*'
doi: 10.1109/TETCI.2024.3500025
abstract: "This paper proposes a novel end-to-end network for Image Manipulation Localization
  (IML) comprising three modules: feature fusion, encoder, and decoder. To address
  the limitations of current DNN-based IML algorithms in accessing global features
  and segmenting tampered edges, we propose a Dual-shallow Feature Pyramid Fusion
  (DFPF) module. The DFPF module integrates semantic and texture features through
  a bidirectional pathway, forming RGB Feature Pyramids (RGBFP) and Local Textual
  Feature Pyramids (LTFP) using dual Hybrid ResNet50s in a ’Siamese' configuration.
  These feature pyramids are merged via multi-scale fusion to enhance global pyramid
  features for decoding. The LTFP branch includes a Pre-processing Block, Parallel
  Multi-Scale Convolution (PMSC), or Channel Split High-frequency Convolution (CSHC)
  to capture local textual features and subtle manipulation traces. The Encoder employs
  Transformer layers for robust global representations. At the same time, the Decoder
  uses Cascaded Boundary Context Inconsistent Enhancement (BCIE) Blocks to reconstruct
  a coarse-to-fine binary mask, enhancing texture inconsistencies at manipulated region
  boundaries. Additionally, we introduce an automated method for generating a large-scale
  forgery dataset via Photoshop Scripting, reducing labor costs. Our model effectively
  locates tampered regions of various shapes and sizes, improving boundary anomaly
  detection. Extensive experimental results demonstrate that our method significantly
  outperforms existing state-of-the-art models."
tags:
- Kernel
- Feature extraction
- Convolution
- Forensics
- Image edge detection
- Decoding
- Location awareness
- Semantics
- Transformers
- boundary contextual incoherence enhancement (BCIE)
- channel split high-frequency convolution (CSHC)
- dual-shallow feature pyramid fusion (DFPF)
- Image manipulation localization (IML)
- parallel multi-scale convolution (PMSC)
- Residual neural networks
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10771742/?arnumber=10771742
---
