---
title: Sliding Window Nonnegative Matrix Factorization (SW-NMF) for Robustness
  Low-Density Myoelectric Signals Decoding Against Electrodes Shift
publication_types:
  - "1"
authors:
  - Zhien Xian
  - Zhiguo Zhang
  - Fei Tang
  - Li Zhang
  - gan-huang
doi: 10.1109/NER.2019.8717174
publication: 2019 9th International IEEE/EMBS Conference on Neural Engineering (NER)
abstract: In this paper, the problem of electrodes shift is studied in
  low-density surface electromyographic (sEMG) based prosthetic control with the
  proposed Sliding Window Nonnegative Matrix Factorization (SW-NMF) algorithm.
  By artificially switching the electrode positions clockwise for π/8, the 8
  channel sEMG signals of 10 gestures were recorded before and after the
  electrodes shift. It is found that electrodes shift makes the feature space of
  the sEMG signal non-stationary, which has a great influence on the classify
  accuracy. Besides, all kinds of existing algorithms for electrodes shift in
  the high-density electrode environment have limited effect in the low-density
  electrode environment. In the proposed SW-NMF method, we firstly place the sum
  constrain on the coefficient matrix H to reduce change of the sample
  distribution in the feature space. Secondly, a sliding widow strategy is
  applied accompany with the sum constrain on H to make the algorithm can be run
  online. Finally, a self-enhanced version of Linear Discriminant Analysis (LDA)
  is included in the SW-NMF algorithm to make the classifier be able to follow
  the change of sample distribution in the feature space for further improve the
  decoding accuracy. Compared with the traditional TD+LDA, and the other type of
  NMF based methods, the result of the proposed SW-NMF shows a high robustness
  for electrodes shift.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2019-03-19T17:26:00.000Z
---
