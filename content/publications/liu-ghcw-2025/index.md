---
title: 'GHCW: A novel Guarded High-fidelity Compression-based Watermarking scheme
  for AI model protection and self-recovery'
authors:
- Tong Liu
- Xiaochen Yuan
- Wei Ke
- Chan-Tong Lam
- Sio-Kei Im
- Xiuli Bi
date: '2025-11-01'
publishDate: '2025-12-15T15:16:09.214857Z'
publication_types:
- article-journal
publication: '*Applied Soft Computing*'
doi: 10.1016/j.asoc.2025.113576
abstract: Artificial Intelligence (AI) models are valuable and frequently face malicious
  tampering attacks, which require significant data and time to retrain when compromised.
  To address this issue, we propose a Guarded Highfidelity Compression-based Watermarking
  (GHCW) scheme for detecting and further recovering the tampered parameters, aiming
  to protect the model’s functional performance without the necessity for retraining.
  In GHCW, the watermark consists of an authentication probe for tamper detection,
  recovery bits, and ciphertext for model recovery. The authentication probe is generated
  by computing inherent characteristics of the parameters using hash algorithms and
  eigenvalue calculations. Different from existing works, the recovery bits are produced
  through a high-fidelity model compression technique, which concentrates key model
  information into fewer high-priority bits. This design enables the recovery mechanism
  to remain effective even under largescale parameter tampering. To protect these
  bits, they are linearly encrypted with a key, generating a ciphertext that serves
  as a guard. To the best of our knowledge, we are one of the first to propose and
  implement this idea in the area of AI model protection. Experimental results demonstrate
  that GHCW excels in recovering models from tampering, especially large-scale parameter
  disturbance. Compared to existing methods, GHCW shows superiority in both model
  recovery and tolerance to tampering rate, tolerating tampering rates up to 70%,
  while existing methods recover at most 50%.
links:
- name: URL
  url: https://linkinghub.elsevier.com/retrieve/pii/S1568494625008877
---
