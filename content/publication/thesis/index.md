---
title: Interpretable Machine Learning for Modeling, Evaluating, and Refining Clinical Decision-Making

authors:
  - Anton Matsson

date: 2025-07-28
doi: ''

publication_types: [thesis]

publication: 'Doctoral dissertation'
publication_short: ''

abstract: |
  Machine learning offers great promise for developing new treatment policies from observational clinical data. However, a key challenge in this offline setting is reliably assessing the performance of new policies. Meaningful evaluation requires that the proposed policy is sufficiently similar to the data-collecting policy—constraining the search for viable policies. In clinical settings, the data-collecting policy is typically unknown, necessitating probabilistic modeling for many evaluation methods. As a result, modeling, evaluating, and refining clinical decision-making are closely interconnected. This thesis explores these tasks with a focus on interpretability, essential for clinical validation and trust.

  First, we examine representations of a patient's medical history that support interpretable policy modeling. As history accumulates over time, creating compact summaries that capture relevant historical aspects becomes increasingly important. Our results show that simple aggregates of past data, combined with the most recent information, allow for accurate and interpretable policy modeling across decision-making tasks. We also propose methods that leverage structure in the data collection process—such as patterns in missing feature values—to further enhance interpretability.   

  Second, in the context of policy evaluation, we emphasize the need for assessments that go beyond estimating overall performance. Specifically, in which situations does the proposed policy differ from current practice? To address this question, we leverage case-based learning to identify a small set of prototypical cases in the observed data that reflect decision-making under current practice. We propose using these prototypes as a diagnostic tool to explain differences between policies, providing a compact and interpretable basis for validating new treatment strategies.

  Third, motivated by the need for interpretable policies that are compatible with offline evaluation, we propose deriving new policies from an interpretable model of existing clinical behavior. By restricting the new policy to select from treatments most commonly observed in each patient state—as described by the model—we enable reliable evaluation. This standardization of frequent treatment patterns may reduce unwarranted practice variability and offers a promising alternative to current practice, as demonstrated in real-world examples from rheumatoid arthritis and sepsis care.

summary: This thesis promotes the use of interpretable machine learning to model observed behavior, enabling the comparison of treatment strategies and quality assessment of policy evaluations. It explores representations of patient data that support interpretable modeling and proposes approaches that leverage structure in the data collection process to improve model interpretability. Finally, it argues that interpretable models of current behavior can inform the design of new policies.

#tags:
#  - reinforcement learning
#  - interpretability
#  - off-policy evaluation

featured: true

url_pdf: https://research.chalmers.se/en/publication/547730
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: A patient meeting where the doctor is supported by data in making clinical decisions (Sanna Lindblom, 2025).
  focal_point: ''
  preview_only: false

projects: []

slides: ''

share: false
reading_time: false
---
