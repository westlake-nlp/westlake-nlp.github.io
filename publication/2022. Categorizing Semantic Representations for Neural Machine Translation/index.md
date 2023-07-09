---
title: 'Categorizing Semantic Representations for Neural Machine Translation'
abstract: Modern neural machine translation (NMT) models have achieved competitive performance in standard benchmarks. However, they have recently been shown to suffer limitation in compositional generalization, failing to effectively learn the translation of atoms (e.g., words) and their semantic composition (e.g., modification) from seen compounds (e.g., phrases), and thus suffering from significantly weakened translation performance on unseen compounds during inference.We address this issue by introducing categorization to the source contextualized representations. The main idea is to enhance generalization by reducing sparsity and overfitting, which is achieved by finding prototypes of token representations over the training set and integrating their embeddings into the source encoding. Experiments on a dedicated MT dataset (i.e., CoGnition) show that our method reduces compositional generalization error rates by 24% error reduction. In addition, our conceptually simple method gives consistently better results than the Transformer baseline on a range of general MT datasets.

publication_types:
  - "1"
authors:
  - Yongjing Yin
  - Yafu Li
  - Fandong Meng
  - Jie Zhou
  - Yue Zhang
# author_notes:
#   - Equal contribution
#   - Equal contribution
publication: "*Proceedings of the 29th International Conference on Computational Linguistics*"
publication_short: "*COLING*"
# summary: Lorem ipsum dolor sit amet, consectetur #adipiscing elit. Duis posuere
#   tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
#   condimentum.
# url_dataset: ""
# url_project: ""
# url_source: ""
# url_video: ""
# url_poster: ""
url_pdf: https://aclanthology.org/2022.coling-1.464.pdf
# url_code: https://github.com/wowchemy/wowchemy-hugo-themes
# url_slides: ""
doi: ""
featured: false
tags:
  - Neural Machine Translation
projects: []
image:
  caption: "[**Url**](./featured.jpg)"
  focal_point: ""
  preview_only: false
date: 2022-10-01T00:00:00.000Z
# publishDate: 2017-01-01T00:00:00.000Z
---
