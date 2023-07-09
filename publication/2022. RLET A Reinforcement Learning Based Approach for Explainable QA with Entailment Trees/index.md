---
title: 'RLET: A Reinforcement Learning Based Approach for Explainable QA with Entailment Trees'
abstract: Interpreting the reasoning process from questions to answers poses a challenge in approaching explainable QA. A recently proposed structured reasoning format, entailment tree, manages to offer explicit logical deductions with entailment steps in a tree structure. To generate entailment trees, prior single pass sequence-to-sequence models lack visible internal decision probability, while stepwise approaches are supervised with extracted single step data and cannot model the tree as a whole. In this work, we propose RLET, a Reinforcement Learning based Entailment Tree generation framework, which is trained utilising the cumulative signals across the whole tree. RLET iteratively performs single step reasoning with sentence selection and deduction generation modules, from which the training signal is accumulated across the tree with elaborately designed aligned reward function that is consistent with the evaluation. To the best of our knowledge, we are the first to introduce RL into the entailment tree generation task. Experiments on three settings of the EntailmentBank dataset demonstrate the strength of using RL framework.

publication_types:
  - "1"
authors:
  - Tengxiao Liu
  - Qipeng Guo
  - Xiangkun Hu
  - Yue Zhang
  - Xipeng Qiu
  - Zheng Zhang
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
url_pdf: https://preview.aclanthology.org/emnlp-22-ingestion/2022.emnlp-main.483.pdf
# url_code: https://github.com/wowchemy/wowchemy-hugo-themes
# url_slides: ""
doi: ""
featured: false
tags:
  - Reinforcement Learning
  - Natural Language Processing
projects: []
image:
  caption: "[**Url**](./featured.jpg)"
  focal_point: ""
  preview_only: false
date: 2022-12-01T00:00:00.000Z
# publishDate: 2017-01-01T00:00:00.000Z
---
