---
title: Dialogue State Tracking with Sparse Local Slot Attention
authors:
- Longfei Yang
- Jiyi Li
- Sheng Li
- Takahiro Shinozaki
date: '2023-07-01'
publishDate: '2024-02-04T16:07:06.860612Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 5th Workshop on NLP for Conversational AI (NLP4ConvAI
  2023)*'
doi: 10.18653/v1/2023.nlp4convai-1.4
abstract: Dialogue state tracking (DST) is designed to track the dialogue state during
  the conversations between users and systems, which is the core of task-oriented
  dialogue systems. Mainstream models predict the values for each slot with fully
  token-wise slot attention from dialogue history. However, such operations may result
  in overlooking the neighboring relationship. Moreover, it may lead the model to
  assign probability mass to irrelevant parts, while these parts contribute little.
  It becomes severe with the increase in dialogue length. Therefore, we investigate
  sparse local slot attention for DST in this work. Slot-specific local semantic information
  is obtained at a sub-sampled temporal resolution capturing local dependencies for
  each slot. Then these local representations are attended with sparse attention weights
  to guide the model to pay attention to relevant parts of local information for subsequent
  state value prediction. The experimental results on MultiWOZ 2.0 and 2.4 datasets
  show that the proposed approach effectively improves the performance of ontology-based
  dialogue state tracking, and performs better than token-wise attention for long
  dialogues.
links:
- name: URL
  url: https://aclanthology.org/2023.nlp4convai-1.4
---
