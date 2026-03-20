---
title: Accessing dynamic functional connectivity using regularized sparse-smooth inverse covariance estimation from fMRI
publication_types:
  - "2"
authors:
  - Li Zhang
  - Zening Fu
  - Wenwen Zhang
  - gan-huang 
  - Zhen Liang
  - Linling Li
  - Bharat B. Biswal
  - Vince D. Calhoun
  - Zhiguo Zhang 
doi: 10.1016/j.neucom.2021.02.081
publication: Neurocomputing
publication_short: NEUROCOMPUTING
abstract: Inferring dynamic functional connectivity (dFC) from functional magnetic resonance imaging (fMRI) is crucial to understand the time-variant functional inter-relationships among brain regions. Because of the sparse property of functional connectivity networks, sparsity-promoting dFC estimation methods, which are mainly based on l1-norm regularization, are gaining popularity. However, l1-norm regularization cannot provide the maximum sparsity solution as the most natural sparsity promoting norm, the l0-norm. But l0-norm is seldom used to infer sparse dFC because an efficient algorithm to address the nonconvexity problem of l0-norm is lacking. In this work, we develop a new l0-norm regularization-based inverse covariance estimation method for estimating dFC from fMRI. This novel method employs l0-norm regularizations on both spatial and temporal scales to enhance the spatial sparsity and temporal smoothness of dFC estimates. To overcome the non-convexity of l0-norm, we further propose an effective optimization algorithm based on the coordinate descent (CD). The performance of the proposed l0-norm-based sparse-smooth regularization (L0-SSR) method is examined using a series of synthetic datasets concerning various types of network topology. We further apply the proposed L0-SSR method to real fMRI data recorded in block-design motor tasks from 45 participants for the exploration of task induced dFC. Results on synthetic and real-world fMRI data show that, the L0-SSR method can achieve more accurate and interpretable dFC estimates than conventional l1-norm-based dFC estimation methods. Hence, the proposed L0-SSR method could serve as a powerful analytical tool to infer highly complex, variable, and sparse dFC patterns.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-03-10T17:41:00.000Z
---
