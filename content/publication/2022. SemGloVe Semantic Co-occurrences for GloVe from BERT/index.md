---
title: 'SemGloVe: Semantic Co-occurrences for GloVe from BERT'
abstract: 'GloVe learns word embeddings by leveraging statistical information from word co-occurrence matrices. However, word pairs in the matrices are extracted from a predefined local context window, which might lead to limited word pairs and potentially semantic irrelevant word pairs. In this paper, we propose SemGloVe, which distillssemantic co-occurrencesfrom BERT into static GloVe word embeddings. Particularly, we propose two models to extract co-occurrence statistics based on either the masked language model or the multi-head attention weights of BERT. Our methods can extract word pairs limited by the local window assumption, and can define the co-occurrence weights by directly considering the semantic distance between word pairs. Experiments on several word similarity datasets and external tasks show that SemGloVe can outperform GloVe.'

publication_types:
  - "2"
authors:
  - Leilei Gan
  - Zhiyang Teng
  - Yue Zhang
  - Linchao Zhu
  - Fei Wu
  - Yi Yang
# author_notes:
#   - Equal contribution
#   - Equal contribution
publication: "*IEEE/ACM Transactions on Audio, Speech and Language Processing*"
publication_short: "*TASLP*"
# summary: Lorem ipsum dolor sit amet, consectetur #adipiscing elit. Duis posuere
#   tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
#   condimentum.
# url_dataset: ""
# url_project: ""
# url_source: ""
# url_video: ""
# url_poster: ""
url_pdf: https://frcchang.github.io/pub/SemGloVe_leileigan.pdf
# url_code: https://github.com/wowchemy/wowchemy-hugo-themes
# url_slides: ""
doi: ""
featured: false
tags:
  - Masked Language Model
  - Natural Language Processing
projects: []
image:
  caption: "[**Url**](./featured.jpg)"
  focal_point: ""
  preview_only: false
date: 2022-11-01T00:00:00.000Z
# publishDate: 2017-01-01T00:00:00.000Z
---
