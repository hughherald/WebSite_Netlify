---
title: Removal of eye-blinking artifacts by ICA in cross-modal long-term EEG recording
publication_types:
  - "1"
authors:
  - gan-huang
  - Zhenxing Hu
  - Li Zhang
  - Linling Li
  - Zhen Liang
  - Zhiguo Zhang
doi: 10.1109/EMBC44109.2020.9176711
publication: 2020 42nd Annual International Conference of the IEEE Engineering
  in Medicine & Biology Society (EMBC)
abstract: Independent Component Analysis (ICA) has became the most popular
  method to remove eye-blinking artifacts from electroencephalogram (EEG)
  recording. For long term EEG recording, ICA was commonly considered to costing
  a lot of computation time. Furthermore, with no ground truth, the discussion
  about the quality of ICA decomposition in a nonstationary environment was
  specious. In this study, we investigated the "signal" (P300 waveform) and the
  "noise" (averaged eye-blinking artifacts) on a cross-modal long-term EEG
  recording to evaluate the efficiency and effectiveness of different methods on
  ICA eye-blinking artifacts removal. As a result, it was found that, firstly,
  down sampling is an effective way to reduce the computation time in ICA.
  Appropriate down sampling ratio could speed up ICA computation 200 times and
  keep the decomposition performance stable, in which the computation time of
  ICA decomposition on a 2800 s EEG recording was less than 5 s. Secondly,
  dimension reduction by PCA was also a way to improve the efficiency and
  effectiveness of ICA. Finally, the comparison by cropping the dataset
  indicated that performing ICA on each run of the experiment separately would
  achieve a better result for eye-blinking artifacts removal than using all the
  EEG data input for ICA.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2020-07-19T17:48:00.000Z
---
