---
title: Unsupervised Domain Adaptation by Learning Using Privileged Information

authors:
  - Adam Breitholtz
  - Anton Matsson
  - Fredrik D. Johansson

author_notes:
- Equal contribution
- Equal contribution

date: 2024-08-17
doi: ''

publication_types: [article-journal]

publication: '*Transactions on Machine Learning Research*'
publication_short: ''

abstract: Successful unsupervised domain adaptation is guaranteed only under strong assumptions such as covariate shift and overlap between input domains. The latter is often violated in high-dimensional applications like image classification which, despite this limitation, continues to serve as inspiration and benchmark for algorithm development. In this work, we show that training-time access to side information in the form of auxiliary variables can help relax restrictions on input variables and increase the sample efficiency of learning at the cost of collecting a richer variable set. As this information is assumed available only during training, not in deployment, we call this problem unsupervised domain adaptation by learning using privileged information (DALUPI). To solve this problem, we propose a simple two-stage learning algorithm, inspired by our analysis of the expected error in the target domain, and a practical end-to-end variant for image classification. We propose three evaluation tasks based on classification of entities in photos and anomalies in medical images with different types of available privileged information (binary attributes and single or multiple regions of interest). We demonstrate across these tasks that using privileged information in learning can reduce errors in domain transfer compared to baselines, be robust to spurious correlations in the source domain, and increase sample efficiency.

summary: Learning using privileged information can improve identification and sample efficiency in unsupervised domain adaptation.

#tags:
#  - unsupervised domain adaptation
#  - privileged information
#  - image classification

featured: true

url_pdf: https://openreview.net/forum?id=saV3MPH0kw
url_code: https://github.com/antmats/dalupi
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  #caption: Examples of domain adaptation tasks with different types of privileged information.
  focal_point: ''
  preview_only: false

projects: []

slides: ''

share: false
reading_time: false
---
