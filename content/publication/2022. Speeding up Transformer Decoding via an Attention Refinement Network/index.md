---
title: 'Speeding up Transformer Decoding via an Attention Refinement Network'
abstract: Despite the revolutionary advances made by Transformer in Neural Machine Translation (NMT), inference efficiency remains an obstacle due to the heavy use of attention operations in auto-regressive decoding. We thereby propose a lightweight attention structure called Attention Refinement Network (ARN) for speeding up Transformer. Specifically, we design a weighted residual network, which reconstructs the attention by reusing the features across layers. To further improve the Transformer efficiency, we merge the self-attention and cross-attention components for parallel computing. Extensive experiments on ten WMT machine translation tasks show that the proposed model yields an average of 1.35x faster (with almost no decrease in BLEU) over the state-of-the-art inference implementation. Results on widely used WMT14 En-De machine translation tasks demonstrate that our model achieves a higher speed-up, giving highly competitive performance compared to AAN and SAN models with fewer parameter numbers.

publication_types:
  - "1"
authors:
  - Kaixin Wu
  - Yue Zhang
  - Bojie Hu
  - Tong Zhang
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
url_pdf: https://aclanthology.org/2022.coling-1.453.pdf
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
