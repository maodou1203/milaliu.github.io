---
title: 'CAMU-Net: Copy-move forgery detection utilizing coordinate attention and multi-scale
  feature fusion-based up-sampling'
authors:
- Kaiqi Zhao
- Xiaochen Yuan
- me
- Yan Xiang
- Zhiyao Xie
- Guoheng Huang
- Li Feng
date: '2024-03-01'
publishDate: '2025-12-15T15:16:09.150005Z'
publication_types:
- article-journal
publication: '*Expert Systems with Applications*'
doi: 10.1016/j.eswa.2023.121918
abstract: In this paper, we construct CAMU-Net, an image forgery detection method,
  to obtain evidence of copy-move forgery areas in images. In CAMU-Net, the hierarchical
  feature extraction stage (HFE_Stage) is used to extract multi-scale key feature
  maps. Next, a hierarchical feature matching stage (HFM_Stage) based on self-correlation
  combined with a multi-scale structure is designed to predict copy-move forgery areas
  with different scales of information. To optimize the matching results, we design
  a coordinate attention-based resource allocation stage (CARA_Stage), which uses
  a location and channel attention mechanism to assign more weight to copymove areas.
  In this way, useful information can be strengthened while irrelevant information
  is suppressed. To effectively use the multi-scale prediction results in the multi-scale
  feature fusion-based up-sampling stage (MFFU_Stage), we integrate the high-level
  and low-level information into one information flow. By combining the global feature
  information of the deep layers and the location details of the shallow layers, the
  performance of CMFD can be improved. To demonstrate the validity of our model, we
  compare it with a variety of traditional methods and deep learning methods. The
  results show that our performance is outstanding. In particular, on the COVERAGE
  dataset, our AUC is 87.3%, which is 2.4% higher than the second place. In addition,
  we design a variety of baseline methods to perform several ablation experiments
  to demonstrate the validity of the modules in this model.
links:
- name: URL
  url: https://linkinghub.elsevier.com/retrieve/pii/S095741742302420X
---
