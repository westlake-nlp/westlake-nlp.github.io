---
title: 'Multi-Granularity Optimization for Non-Autoregressive Translation'
abstract: Despite low latency, non-autoregressive machine translation (NAT) suffers severe performance deterioration due to the naive independence assumption. This assumption is further strengthened by cross-entropy loss, which encourages a strict match between the hypothesis and the reference token by token. To alleviate this issue, we propose multi-granularity optimization for NAT, which collects model behaviours on translation segments of various granularities and integrates feedback for backpropagation. Experiments on four WMT benchmarks show that the proposed method significantly outperforms the baseline models trained with cross-entropy loss, and achieves the best performance on WMT’16 En⇔Ro and highly competitive results on WMT’14 En⇔De for fully non-autoregressive translation.

publication_types:
  - "1"
authors:
  - Yafu Li
  - Leyang Cui
  - Yongjing Yin
  - Yue Zhang
# author_notes:
#   - Equal contribution
#   - Equal contribution
publication: "*Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing*"
publication_short: "*EMNLP*"
# summary: Lorem ipsum dolor sit amet, consectetur #adipiscing elit. Duis posuere
#   tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
#   condimentum.
# url_dataset: ""
# url_project: ""
# url_source: ""
# url_video: ""
# url_poster: ""
url_pdf: https://preview.aclanthology.org/emnlp-22-ingestion/2022.emnlp-main.339.pdf
# url_code: https://github.com/wowchemy/wowchemy-hugo-themes
# url_slides: ""
doi: ""
featured: false
tags:
  - Machine Translation
projects: []
image:
  caption: "[**Url**](./featured.jpg)"
  focal_point: ""
  preview_only: false
date: 2022-12-01T00:00:00.000Z
# publishDate: 2017-01-01T00:00:00.000Z
---
