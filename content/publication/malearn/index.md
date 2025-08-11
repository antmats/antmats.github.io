---
title: Prediction Models That Learn to Avoid Missing Values

authors:
  - Lena Stempfle
  - Anton Matsson
  - Newton Mwai
  - Fredrik D. Johansson

author_notes:
- Equal contribution
- Equal contribution

date: 2025-05-06
doi: ''

publication_types: [paper-conference]

publication: To appear in *Proceedings of the 42nd International Conference on Machine Learning*
publication_short: ''

abstract: Handling missing values at test time is challenging for machine learning models, especially when aiming for both high accuracy and interpretability. Established approaches often add bias through imputation or excessive model complexity via missingness indicators. Moreover, either method can obscure interpretability, making it harder to understand how the model utilizes the observed variables in predictions. We propose missingness-avoiding (MA) machine learning, a general framework for training models to rarely require the values of missing (or imputed) features at test time. We create tailored MA learning algorithms for decision trees, tree ensembles, and sparse linear models by incorporating classifier-specific regularization terms in their learning objectives. The tree-based models leverage contextual missingness by reducing reliance on missing values based on the observed context. Experiments on real-world datasets demonstrate that MA-DT, MA-LASSO, MA-RF, and MA-GBT effectively reduce the reliance on features with missing values while maintaining predictive performance competitive with their unregularized counterparts. This shows that our framework gives practitioners a powerful tool to maintain interpretability in predictions with test-time missing values.

summary: We introduce missingness-avoiding machine learning—a general framework for training models that are unlikely to rely on features that may be missing at test time.

#tags:
#  - missing values
#  - interpretability
#  - supervised learning

featured: true

url_pdf: https://openreview.net/pdf?id=ps3aO9MHJv
url_code: https://github.com/antmats/malearn
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  #caption: A standard decision tree vs. a missingness-avoiding decision tree.
  focal_point: ''
  preview_only: false

projects: []

slides: ''

share: false
reading_time: false
---
