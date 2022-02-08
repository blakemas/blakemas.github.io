---
title: "Learning nearest neighbor graphs from noisy distance samples"
collection: publications
permalink: /publication/2019-12-07-noisy-nn-graph
excerpt: 'We consider the problem of actively learning the nearest neighbor graph of a dataset of n items in as few queries as possible.'
date: 2019-12-07
venue: 'Neural Information Processing Systems'
paperurl: 'https://proceedings.neurips.cc/paper/2019/file/98c56bce74669e2e4e7a9fc1caa8c326-Paper.pdf'
citation: '<b>Mason, B.</b>, Tripathy, A., & Nowak, R. (2019). Learning nearest neighbor graphs from noisy distance samples. <i>Advances in Neural Information Processing Systems</i>, 32.'
---

We consider the problem of learning the nearest neighbor graph of a dataset of n items. The metric is unknown, but we can query an oracle to obtain a noisy estimate of the distance between any pair of items. This framework applies to problem domains where one wants to learn people's preferences from responses commonly modeled as noisy distance judgments. In this paper, we propose an active algorithm to find the graph with high probability and analyze its query complexity. In contrast to existing work that forces Euclidean structure, our method is valid for general metrics, assuming only symmetry and the triangle inequality. Furthermore, we demonstrate efficiency of our method empirically and theoretically, needing only O (n\log (n)\Delta^{-2}) queries in favorable settings, where\Delta^{-2} accounts for the effect of noise. Using crowd-sourced data collected for a subset of the UT~ Zappos50K dataset, we apply our algorithm to learn which shoes people believe are most similar and show that it beats both an active baseline and ordinal embedding.

[Download paper here](https://proceedings.neurips.cc/paper/2019/file/98c56bce74669e2e4e7a9fc1caa8c326-Paper.pdf)

Recommended citation: <b>Mason, B.</b>, Tripathy, A., & Nowak, R. (2019). Learning nearest neighbor graphs from noisy distance samples. <i>Advances in Neural Information Processing Systems</i>, 32.