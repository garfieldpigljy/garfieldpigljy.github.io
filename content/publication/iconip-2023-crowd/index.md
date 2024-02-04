---
title: Learning Representations for Sparse Crowd Answers
authors:
- Jiyi Li
date: '2023-01-01'
publishDate: '2024-02-04T16:07:06.869491Z'
publication_types:
- paper-conference
publication: '*Neural Information Processing: 30th International Conference, ICONIP
  2023, Changsha, China, November 20–23, 2023, Proceedings, Part VI*'
doi: 10.1007/978-981-99-8076-5_34
abstract: When collecting answers from crowds, if there are many instances, each worker
  can only provide the answers to a small subset of the instances, and the instance-worker
  answer matrix is thus sparse. The solutions for improving the quality of crowd answers
  such as answer aggregation are usually proposed in an unsupervised fashion. In this
  paper, for enhancing the quality of crowd answers used for inferring true answers,
  we propose a solution with a self-supervised fashion to effectively learn the potential
  information in the sparse crowd answers. We propose a method named CrowdLR which
  first learns rich instance and worker representations from the crowd answers based
  on two types of self-supervised signals. We create a multi-task model with a Siamese
  structure to learn two classification tasks for two self-supervised signals in one
  framework. We then utilize the learned representations to complete the answers to
  fill the missing answers, and can utilize the answer aggregation methods to the
  complete answers. The experimental results based on real datasets show that our
  approach can effectively learn the representations from crowd answers and improve
  the performance of answer aggregation especially when the crowd answers are sparse.
tags:
- Representation Learning
- Answer Aggregation
- Crowdsourcing
links:
- name: URL
  url: https://doi.org/10.1007/978-981-99-8076-5_34
---
