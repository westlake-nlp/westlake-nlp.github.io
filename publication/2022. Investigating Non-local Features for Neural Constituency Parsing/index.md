---
title: 'Investigating Non-local Features for Neural Constituency Parsing'
abstract: Thanks to the strong representation power of neural encoders, neural chart-based parsers have achieved highly competitive performance by using local features. Recently, it has been shown that non-local features in CRF structures lead to improvements. In this paper, we investigate injecting non-local features into the training process of a local span-based parser, by predicting constituent n-gram non-local patterns and ensuring consistency between non-local patterns and local constituents. Results show that our simple method gives better results than the self-attentive parser on both PTB and CTB. Besides, our method achieves state-of-the-art BERT-based performance on PTB (95.92 F1) and strong performance on CTB (92.31 F1). Our parser also outperforms the self-attentive parser in multi-lingual and zero-shot cross-domain settings.

publication_types:
  - "1"
authors:
  - Leyang Cui
  - Sen Yang
  - Yue Zhang
# author_notes:
#   - Equal contribution
#   - Equal contribution
publication: "*Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics*"
publication_short: "*ACL*"
# summary: Lorem ipsum dolor sit amet, consectetur #adipiscing elit. Duis posuere
#   tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
#   condimentum.
# url_dataset: ""
# url_project: ""
# url_source: ""
# url_video: ""
# url_poster: ""
url_pdf: https://aclanthology.org/2022.acl-long.146.pdf
# url_code: https://github.com/wowchemy/wowchemy-hugo-themes
# url_slides: ""
doi: ""
featured: false
tags:
  - Parsing
projects: []
image:
  caption: "[**Url**](./featured.jpg)"
  focal_point: ""
  preview_only: false
date: 2022-05-01T00:00:00.000Z
# publishDate: 2017-01-01T00:00:00.000Z
---
