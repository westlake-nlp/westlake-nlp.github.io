---
title: 'Mere Contrastive Learning for Cross-Domain Sentiment Analysis'
abstract: Cross-domain sentiment analysis aims to predict the sentiment of texts in the target domain using the model trained on the source domain to cope with the scarcity of labeled data. Previous studies are mostly cross-entropy-based methods for the task, which suffer from instability and poor generalization. In this paper, we explore contrastive learning on the cross-domain sentiment analysis task. We propose a modified contrastive objective with in-batch negative samples so that the sentence representations from the same class can be pushed close while those from the different classes become further apart in the latent space. Experiments on two widely used datasets show that our model can achieve state-of-the-art performance in both cross-domain and multi-domain sentiment analysis tasks. Meanwhile, visualizations demonstrate the effectiveness of transferring knowledge learned in the source domain to the target domain and the adversarial test verifies the robustness of our model.

publication_types:
  - "1"
authors:
  - Yun Luo
  - Fang Guo
  - Zihan Liu,
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
url_pdf: https://aclanthology.org/2022.coling-1.620.pdf
# url_code: https://github.com/wowchemy/wowchemy-hugo-themes
# url_slides: ""
doi: ""
featured: false
tags:
  - Sentiment Analysis
  - Contrastive Learning
projects: []
image:
  caption: "[**Url**](./featured.jpg)"
  focal_point: ""
  preview_only: false
date: 2022-10-01T00:00:00.000Z
# publishDate: 2017-01-01T00:00:00.000Z
---
