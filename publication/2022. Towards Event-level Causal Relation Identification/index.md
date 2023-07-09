---
title: 'Towards Event-Level Causal Relation Identification'
abstract: |-
  Existing methods usually identify causal relations between events at the mention-level, which takes each event mention pair as a separate input. As a result, they either suffer from conflicts among causal relations predicted separately or require a set of additional constraints to resolve such conflicts. We propose to study this task in a more realistic setting, where event-level causality identification can be made. The advantage is two folds: 1) with modeling different mentions of an event as a single unit, no more conflicts among predicted results, without any extra constraints; 2) with the use of diverse knowledge sources (e.g., co-occurrence and coreference relations), a rich graph-based event structure can be induced from the document for supporting event-level causal inference. Graph convolutional network is used to encode such structural information, which aims to capture the local and non-local dependencies among nodes. Results show that our model achieves the best performance under both mention- and event-level settings, outperforming a number of strong baselines by at least 2.8% on F1 score.

publication_types:
  - "1"
authors:
  - Chuang Fan
  - Daoxing Liu
  - Libo Qin,
  - Yue Zhang
  - Ruifeng Xu
# author_notes:
#   - Equal contribution
#   - Equal contribution
publication: "*Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval*"
publication_short: "*SIGIR*"
# summary: Lorem ipsum dolor sit amet, consectetur #adipiscing elit. Duis posuere
#   tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
#   condimentum.
# url_dataset: ""
# url_project: ""
# url_source: ""
# url_video: ""
# url_poster: ""
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3477495.3531758?casa_token=_fyqeDP_TCEAAAAA:nX-R6gdMwBbvS6T93wMMALtF--0B5oDmGH00BMuo31fNJjpf0nJ3vH2vPovlg1G-BwCW8yboXpo3rLQ
# url_code: https://github.com/wowchemy/wowchemy-hugo-themes
# url_slides: ""
doi: ""
featured: false
tags:
  - Information Retrieval
projects: []
image:
  caption: "[**Url**](./featured.jpg)"
  focal_point: ""
  preview_only: false
date: 2022-07-01T00:00:00.000Z
# publishDate: 2017-01-01T00:00:00.000Z
---
