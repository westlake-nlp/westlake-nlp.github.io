---
title: 'USB: A Unified Semi-supervised Learning Benchmark for Classification'
abstract: Semi-supervised learning (SSL) improves model generalization by leveraging massive unlabeled data to augment limited labeled samples. However, currently, popular SSL evaluation protocols are often constrained to computer vision (CV) tasks. In addition, previous work typically trains deep neural networks from scratch, which is time-consuming and environmentally unfriendly. To address the above issues, we construct a Unified SSL Benchmark (USB) for classification by selecting 15 diverse, challenging, and comprehensive tasks from CV, natural language processing (NLP), and audio processing (Audio), on which we systematically evaluate the dominant SSL methods, and also open-source a modular and extensible codebase for fair evaluation of these SSL methods. We further provide the pretrained versions of the state-of-the-art neural models for CV tasks to make the cost affordable for further tuning. USB enables the evaluation of a single SSL algorithm on more tasks from multiple domains but with less cost. Specifically, on a single NVIDIA V100, only 39 GPU days are required to evaluate FixMatch on 15 tasks in USB while 335 GPU days (279 GPU days on 4 CV datasets except for ImageNet) are needed on 5 CV tasks with TorchSSL.

publication_types:
  - "1"
authors:
  - Yidong Wang
  - Hao Chen
  - Yue Fan
  - Wang Sun
  - Ran Tao
  - Wenxin Hou
  - Renjie Wang
  - Linyi Yang
  - Zhi Zhou
  - Lan-Zhe Guo
  - Heli Qi
  - Zhen Wu
  - Yu-Feng Li
  - Satoshi Nakamura
  - Wei Ye
  - Marios Savvides
  - Bhiksha Raj
  - Takahiro Shinozaki
  - Bernt Schiele
  - Jindong Wang
  - Xing Xie
  - Yue Zhang
# author_notes:
#   - Equal contribution
#   - Equal contribution
publication: "*Proceedings of the Thirty-sixth Conference on Neural Information Processing Systems Datasets and Benchmarks Track*"
publication_short: "*NeurIPS*"
# summary: Lorem ipsum dolor sit amet, consectetur #adipiscing elit. Duis posuere
#   tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
#   condimentum.
# url_dataset: ""
# url_project: ""
# url_source: ""
# url_video: ""
# url_poster: ""
url_pdf: https://arxiv.org/pdf/2208.07204.pdf
# url_code: https://github.com/wowchemy/wowchemy-hugo-themes
# url_slides: ""
doi: ""
featured: false
tags:
  - Datasets and Benchmarks
projects: []
image:
  caption: "[**Url**](./featured.jpg)"
  focal_point: ""
  preview_only: false
date: 2022-10-01T00:00:00.000Z
# publishDate: 2017-01-01T00:00:00.000Z
---
