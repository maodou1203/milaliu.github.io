---
title: A Symmetric Self-Embedding Mechanism for High-Fidelity Image Recovery Against
  Tampering
authors:
- me
- Xiaochen Yuan
- Wei Ke
- Chan-Tong Lam
- Sio-Kei Im
- Pedro Martins
date: '2025-12-01'
publishDate: '2025-12-15T15:16:09.262209Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Information Forensics and Security*'
doi: 10.1109/TIFS.2025.3638170
abstract: Digital images are inherently fragile and vulnerable to malicious tampering,
  significantly compromising their authenticity and integrity. Image recovery is crucial
  for restoring altered content and preserving the reliability of digital images.
  Traditional fragile watermarking methods achieve high-quality recovery but fail
  under post-processing attacks, while existing deep learning-based approaches offer
  some robustness, yet often produce lower-quality recovered images, typically with
  a PSNR of around 28 dB. To address these challenges, we propose a novel Symmetric
  Self-embedding Mechanism for High-Fidelity Image Recovery against tampering (SSEM-HIR),
  which is capable of restoring tampered images with high quality while maintaining
  some robustness against common attacks. Unlike existing methods that use the fragility
  of watermarking solely for tampering localization, SSEM-HIR is the first work to
  integrate fragility with spatial symmetry, enabling high-quality tampering recovery.
  Specifically, our SSEM-HIR employs a hierarchical watermark embedding module to
  embed an inverted version of the original image, utilizing spatial symmetry to retrieve
  lost information from the extracted watermark. To further improve recovery quality,
  we design a Dual-branch Region-based SelfRecovery module, where a Spatial-based
  Watermark Extraction block restores tampered regions using embedded watermark information,
  while a Frequency-assisted Image Repair block compensates for quality degradation
  in the untampered area. Extensive experiments show that our method achieves an average
  PSNR of 34.14 dB under common attack scenarios, including noise addition, image
  scaling, Gaussian blurring, and no postprocessing. This represents an improvement
  of over 5 dB and 18% in recovered image quality compared to state-of-the-art approaches.
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/11270957/
---
