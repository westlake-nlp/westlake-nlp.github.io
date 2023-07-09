---
title: 'Balancing Precision and Recall for Neural Biomedical Event Extraction'
abstract: Biomedical event extraction is an essential task in the biomedical research. Existing models suffer from the issue of low recall due to the large proportion of unrecognized events and inflexible event argument combination. To address this issue, we propose an end-to-end multi-task approach for biomedical event extraction. Our model is able to achieve balanced precision and recall with several nichetargeting designs. First, neural encoders with rich lexical and syntactic features are used and shared by multiple subtasks such as event trigger recognition and argument relation extraction, in order to enhance the generalizability of the model. Second, a novel auxiliary subtask is added to identify the proteins that participate in the events, which helps decreasing the challenge of mining event-related proteins from the large candidate space. Third, event argument combination is performed using a strong neural network rather than inflexible rules or templates, to further increase the recall, especially for complex nested events. To demonstrate the effectiveness of our model, we evaluate it on two widely-used biomedical event extraction datasets used in the BioNLP 2011 and 2013 shared tasks. Our model achieves the state-of-the-art results (63.15% and 55.67% in F1 score) by significantly improving the recalls (compared with DeepEvnetMineSciBERT , 4.65% and 5.0%) on the two datasets. Further experiments and analyses show the effectiveness of our proposed features and modules in the model.

publication_types:
  - "2"
authors:
  - Fangfang Su
  - Yue Zhang
  - Fei Li
  - Donghong Ji
# author_notes:
#   - Equal contribution
#   - Equal contribution
publication: "*IEEE/ACM Transactions on Audio, Speech, and Language Processing*"
publication_short: "*TASLP*"
# summary: Lorem ipsum dolor sit amet, consectetur #adipiscing elit. Duis posuere
#   tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
#   condimentum.
# url_dataset: ""
# url_project: ""
# url_source: ""
# url_video: ""
# url_poster: ""
url_pdf: https://frcchang.github.io/pub/Balancing_Precision_and_Recall_for_Neural_Biomedical_Event_Extraction.pdf
# url_code: https://github.com/wowchemy/wowchemy-hugo-themes
# url_slides: ""
doi: ""
featured: false
tags:
  - Natural Language Processing
projects: []
image:
  caption: "[**Url**](./featured.jpg)"
  focal_point: ""
  preview_only: false
date: 2022-11-01T00:00:00.000Z
# publishDate: 2017-01-01T00:00:00.000Z
---
