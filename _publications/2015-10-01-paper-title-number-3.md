---
title: "FITNESS:(Fine Tune on New and Similar Samples) to detect anomalies in streams with drift and outliers"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
# excerpt: 'We propose FITNESS, (Fine Tune on New and Similar Samples), a flexible framework for detecting anomalies on data streams. We show that in case when the data stream has a gaussian distribution, FITNESS is provably both robust and adaptive. The core of our method is to finetune the anomaly detection system only on recent, similar examples, before predicting an anomaly score.'
# date: 2015-10-01
venue: 'International Conference on Machine Learning (ICML), 2022.'
paperurl: 'https://proceedings.mlr.press/v162/sankararaman22a/sankararaman22a.pdf'
# citation: 'Abishek Sankararaman, Balakrishnan Narayanaswamy, Vikramank Y Singh, Zhao Song'
---

_Abishek Sankararaman, Balakrishnan Narayanaswamy, **Vikramank Y Singh**, Zhao Song_

Technology improvements have made it easier than ever to collect diverse telemetry at high resolution from any cyber or physical system, for both monitoring and control. In the domain of monitoring, anomaly detection has become an important problem in many research areas ranging from IoT and sensor networks to devOps. These systems operate in real, noisy and non-stationary environments. A fundamental question is then, ‘How to quickly spot anomalies in a data-stream, and differentiate them from either sudden or gradual drifts in the normal behaviour?’ Although several heuristics have been proposed for detecting anomalies on streams, no known method has formalized the desiderata and rigorously proven that they can be achieved. We begin by formalizing the problem as a sequential estimation task. We propose FITNESS, (Fine Tune on New and Similar Samples), a flexible framework for detecting anomalies on data streams. We show that in the case when the data stream has a gaussian distribution, FITNESS is provably both robust and adaptive. The core of our method is to finetune the anomaly detection system only on recent, similar examples, before predicting an anomaly score. We prove that this is sufficient for robustness and adaptivity. We further experimentally demonstrate that FITNESS is flexible in practice, i.e., it can convert existing offline AD algorithms in to robust and adaptive online ones.

[Download paper here](https://proceedings.mlr.press/v162/sankararaman22a/sankararaman22a.pdf)

<!-- Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>Journal 1</i>. 1(3). -->