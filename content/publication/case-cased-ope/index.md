---
title: Case-Based Off-Policy Evaluation Using Prototype Learning

authors:
  - Anton Matsson
  - Fredrik D. Johansson

date: 2022-05-16
doi: ''

publication_types: [paper-conference]

publication: In *Proceedings of the 38th Conference on Uncertainty in Artificial Intelligence*
publication_short: ''

abstract: Importance sampling (IS) is often used to perform off-policy evaluation but it is prone to several issues—especially when the behavior policy is unknown and must be estimated from data. Significant differences between target and behavior policies can result in uncertain value estimates due to, for example, high variance. Standard practices such as inspecting IS weights may be insufficient to diagnose such problems and determine for which type of inputs the policies differ in suggested actions and resulting values. To address this, we propose estimating the behavior policy for IS using prototype learning. The learned prototypes provide a condensed summary of the input-action space, which allows for describing differences between policies and assessing the support for evaluating a certain target policy. In addition, we can describe a value estimate in terms of prototypes to understand which parts of the target policy have the most impact on the estimate. We find that this provides new insights in the examination of a learned policy for sepsis management. Moreover, we study the bias resulting from restricting models to use prototypes, how bias propagates to IS weights and estimated values and how this varies with history length.

summary: We estimate the behavior policy $\mu$ for OPE using prototypes, allowing us to describe differences between $\mu$ and the target policy $\pi$ and their estimated values.

#tags:
#  - off-policy evaluation
#  - importance sampling
#  - prototype learning

featured: true

url_pdf: https://proceedings.mlr.press/v180/matsson22a.html
url_code: https://github.com/antmats/case_based_ope
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  #caption: Estimating a behavior policy $\mu$ using prototypes allows for describing differences between $\mu$ and a target policy $\pi$.
  focal_point: ''
  preview_only: false

projects: []

slides: ''

share: false
reading_time: false
---
