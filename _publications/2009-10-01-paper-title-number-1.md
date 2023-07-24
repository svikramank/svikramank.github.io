---
title: "C-GATS: Conditional generation of anomalous time series"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-1
venue: 'Neural Information Processing Systems (NeurIPS 2022), SyntheticData4ML Workshop.'
---

_**Vikramank Singh**, Abishek Sankararaman, Balakrishnan Murali Narayanaswamy, Zhao Song_

Sparsity of the data needed to learn about the anomalies is often a key challenge that is faced when it comes to training deep supervised models for the task of Anomaly Detection (AD). Generating synthetic data by applying pre-determined transformations that conform to a set of known invariances has shown to improve performance of such deep models. In this work we present C-GATS to show that one can learn a much larger invariance space using the available sparse data by training a conditional generative model to do Data Augmentation (DA) for anomalous Time Series (TS) in a model-agnostic way. Particularly, we factorize an anomalous TS sequence into 3 attributes— normal sub-sequence, anomalous sub-sequence, and position of the anomaly and model each of them separately. This factorization helps exploit samples from the dominant class i.e normal TS to train a generative model for the sparse class i.e anomalous TS. We provide an exhaustive study to showcase that C-GATS not only learns to generate different types of anomalies (eg: point anomalies and level-shift) but those generated anomalies improve performance of multiple SOTA TS AD models on a set of popular public TS AD benchmark datasets.

[Download paper here](https://openreview.net/pdf?id=7tMRd6-5lPw)

<!-- Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>Journal 1</i>. 1(3). -->