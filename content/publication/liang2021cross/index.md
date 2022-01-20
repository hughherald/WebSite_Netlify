---
title: Cross-Individual Affective Detection Using EEG Signals with Audio-Visual
  Embedding
publication_types:
  - "2"
authors:
  - Zhen Liang
  - Xihao Zhang
  - Rushuang Zhou
  - Li Zhang
  - Linling Li
  - Gan Huang
  - Zhiguo Zhang
doi: doi.org/10.1101/2021.08.06.455362
publication: bioRxiv
abstract: EEG signals have been successfully used in affective detection
  applications, which could directly capture brain dynamics and reflect
  emotional changes at a high temporal resolution. However, the generalized
  ability of the model across individuals has not been thoroughly developed yet.
  An involvement of other data modality, such as audio-visual information which
  are used for emotion triggering, could be beneficial to estimate intrinsic
  emotions in video content and solve the individual differences problem. In
  this paper, we propose a novel deep affective detection model, named as EEG
  with audio-visual embedding (EEG-AVE), for cross-individual affective
  detection. Here, EEG signals are exploited to identify the individualized
  patterns and contribute the individual preferences in affective detection;
  while audio-visual information is leveraged to estimate the intrinsic emotions
  involved in the video content and enhance the reliability of the affective
  detection performance. For EEG-based individual preferences prediction, a
  multi-scale domain adversarial neural network is developed to explore the
  shared dynamic, informative, and domain-invariant EEG features across
  individuals. For video-based intrinsic emotions estimation, a deep
  audio-visual feature based hypergraph clustering method is proposed to examine
  the latent relationship between semantic audio-visual features and emotions.
  Through an embedding model, both estimated individual preferences and
  intrinsic emotions are incorporated with shared weights and further are used
  together to contribute to affective detection across individuals. We conduct
  cross-individual affective detection experiments on MAHNOB-HCI database for
  model evaluation and comparison. The results show our proposed EEG-AVE model
  achieves a better performance under a leave-one-individual-out
  cross-validation individual-independent evaluation protocol, with the
  accuracies of 90.21% and 85.59% for valence and arousal using aggregated
  labels and 71.13% and 66.47% for valence and arousal using non-aggregated
  labels. Hence, EEG-AVE is an effective model with good generalizability, which
  makes it a power tool for cross-individual emotion detection in real-life
  applications.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-08-06T15:32:45.826Z
---
