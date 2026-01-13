---
layout: page
title: Spike Detection
description: Nested Deep Learning Model Towards a Foundation Model for Brain Signal Data
img: assets/img/eegdata.jpg
importance: 1
category: healthcare
related_publications: true
---

### Abstract

Epilepsy affects over 50 million people globally, with EEG/MEG-based spike detection playing a crucial role in diagnosis and treatment.
Manual spike identification is time-consuming and requires specialized training, limiting the number of professionals available to analyze EEG/MEG data.
To address this, various algorithmic approaches have been developed.
However, current methods face challenges in handling varying channel configurations and in identifying the specific channels where spikes originate.
This paper introduces a novel Nested Deep Learning (NDL) framework designed to overcome these limitations.
NDL applies a weighted combination of signals across all channels, ensuring adaptability to different channel setups, and allows clinicians to identify key channels more accurately.
Through theoretical analysis and empirical validation on real EEG/MEG datasets, NDL demonstrates superior accuracy in spike detection and channel localization compared to traditional methods.
The results show that NDL improves prediction accuracy, supports cross-modality data integration, and can be fine-tuned for various neurophysiological applications.

**Keywords**: epilepsy, EEG, MEG, spike detection, deep learning, neuroimaging.

---

<em>Please refer to [the arXiv preprint](https://arxiv.org/abs/2410.03191) of NDL.</em>

<em>Please cite {% cite wei2024nesteddeeplearningmodel %}.</em>

<em>The replication code is available at [GitHub (NDL Replication Code)](https://github.com/shirleyweify/NDL_Replication_Code.git).</em>
