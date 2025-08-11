---
title: Pragmatic Policy Development via Interpretable Behavior Cloning

authors:
  - Anton Matsson
  - Yaochen Rao
  - Heather J. Litman
  - Fredrik D. Johansson

date: 2025-07-22
doi: ''

publication_types: [preprint]

publication: '*arXiv preprint*'
publication_short: ''

abstract: >
  Offline reinforcement learning (RL) holds great promise for deriving optimal
  policies from observational data, but challenges related to interpretability
  and evaluation limit its practical use in safety-critical domains.
  Interpretability is hindered by the black-box nature of unconstrained RL
  policies, while evaluation—typically performed off-policy—is sensitive to
  large deviations from the data-collecting behavior policy, especially when
  using methods based on importance sampling. To address these challenges, we
  propose a simple yet practical alternative: deriving treatment policies from
  the most frequently chosen actions in each patient state, as estimated by an
  interpretable model of the behavior policy. By using a tree-based model,
  which is specifically designed to exploit patterns in the data, we obtain a
  natural grouping of states with respect to treatment. The tree structure
  ensures interpretability by design, while varying the number of actions
  considered controls the degree of overlap with the behavior policy, enabling
  reliable off-policy evaluation. This pragmatic approach to policy development
  standardizes frequent treatment patterns, capturing the collective clinical
  judgment embedded in the data. Using real-world examples in rheumatoid
  arthritis and sepsis care, we demonstrate that policies derived under this
  framework can outperform current practice, offering interpretable
  alternatives to those obtained via offline RL.

summary: We introduce an interpretable, tree-based approach for deriving treatment policies from frequent clinician actions, enabling reliable evaluation and outperforming current practice in real-world care.

#tags:
#  - reinforcement learning
#  - interpretability
#  - off-policy evaluation

featured: true

url_pdf: https://arxiv.org/abs/2507.17056
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  #caption: Average change in disease activity when replacing current practice with each proposed policy.
  focal_point: ''
  preview_only: false

projects: []

slides: ''

share: false
reading_time: false
---
