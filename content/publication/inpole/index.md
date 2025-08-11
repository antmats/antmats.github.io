---
title: How Should We Represent History in Interpretable Models of Clinical Policies?

authors:
  - Anton Matsson
  - Lena Stempfle
  - Yaochen Rao
  - Zachary R. Margolin
  - Heather J. Litman
  - Fredrik D. Johansson

date: 2024-11-02
doi: ''

publication_types: [paper-conference]

publication: In *Proceedings of the 4th Machine Learning for Health Symposium*
publication_short: ''

abstract: Modeling policies for sequential clinical decision-making based on observational data is useful for describing treatment practices, standardizing frequent patterns in treatment, and evaluating alternative policies. For each task, it is essential that the policy model is interpretable. Learning accurate models requires effectively capturing a patient’s state, either through sequence representation learning or carefully crafted summaries of their medical history. While recent work has favored the former, it remains a question as to how histories should best be represented for interpretable policy modeling. Focused on model fit, we systematically compare diverse approaches to summarizing patient history for interpretable modeling of clinical policies across four sequential decision-making tasks. We illustrate differences in the policies learned using various representations by breaking down evaluations by patient subgroups, critical states, and stages of treatment, highlighting challenges specific to common use cases. We find that interpretable sequence models using learned representations perform on par with black-box models across all tasks. Interpretable models using hand-crafted representations perform substantially worse when ignoring history entirely, but are made competitive by incorporating only a few aggregated and recent elements of patient history. The added benefits of using a richer representation are pronounced for subgroups and in specific use cases. This underscores the importance of evaluating policy models in the context of their intended use.

summary: Summarizing patient history through aggregation and truncation allows for interpretable and accurate modeling of policies in sequential decision-making.

#tags:
#  - sequential decision making
#  - policy modeling
#  - interpretable machine learning

featured: true

url_pdf: https://arxiv.org/abs/2412.07895
url_code: https://github.com/antmats/inpole
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []

slides: ''

share: false
reading_time: false
---
