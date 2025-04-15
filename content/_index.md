---
title: ''
date: 2025-01-13
type: landing
design:
  spacing: 5rem
sections:
  - block: community/resume-biography
    content:
      username: admin
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: |
        - **[Apr 2025]** The date is set for my PhD defense! I will defend my thesis on August 27 at 9:00 AM. More details to follow.
        - **[Nov 2024]** My paper on [representing patient history for interpretable policy modeling](https://arxiv.org/abs/2412.07895) has been accepted to ML4H 2024.
        - **[Sep 2024]** My paper on [unsupervised domain adaptation by learning using privileged information](https://openreview.net/forum?id=saV3MPH0kw) has been accepted to TMLR.
        - **[Apr 2024]** As one of six selected students, I am pitching my research in the [Three Minute Thesis (3MT) competition](https://www.vetenskapsfestivalen.se/for-alla/3mt-competition/6335/) on April 21 during the annual popular science festival in Gothenburg.
        - **[Jan 2024]** My paper on [treatment patterns in rheumatoid arthritis](https://doi.org/10.1002/acr2.11621) has been published in ACR Open Rheumatology.
    design:
      columns: '1'
      spacing:
        padding: ['10', '0', '10', '0']
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: ['0', '0', '0', '0']
---
