---
title: 'VideoTemp-o3: Harmonizing Temporal Grounding and Video Understanding in Agentic
  Thinking-with-Videos'
authors:
- Wenqi Liu
- Yunxiao_Wang
- Shijie Ma
- Meng Liu
- Qile Su
- Tianke Zhang
- Haonan Fan
- Changyi Liu
- Kaiyu Jiang
- Jiankang Chen
- Kaiyu Tang
- Bin Wen
- Fan Yang
- Tingting Gao
- Han Li
- Yinwei Wei
- Xuemeng Song
author_notes:
- Equal contribution
- Equal contribution
- Equal contribution
date: '2026-07-01'
publishDate: '2026-08-24T00:00:00Z'
publication_types:
- paper-conference
publication: '*Proceedings of the International Conference on Machine Learning*'
publication_short: "*ICML 2026*"

summary: ICML 2026

abstract: >-
  In long-video understanding, conventional uniform frame sampling often fails to capture key visual evidence,
  leading to degraded performance and increased hallucinations. To address this, recent agentic thinking-with-
  videos paradigms have emerged, adopting a localize-clip-answer pipeline in which the model actively identifies
  relevant video segments, performs dense sampling within those clips, and then produces answers. However,
  existing methods remain inefficient, suffer from weak localization, and adhere to rigid workflows. To solve
  these issues, we propose VideoTemp-o3, a unified agentic thinking-with-videos framework that jointly models
  video grounding and question answering. VideoTemp-o3 exhibits strong localization capability, supports on-
  demand clipping, and can refine inaccurate localizations. Specifically, in the supervised fine-tuning stage,
  we design a unified masking mechanism that encourages exploration while preventing noise. For reinforcement
  learning, we introduce dedicated rewards to mitigate reward hacking. Besides, from the data perspective, we
  develop an effective pipeline to construct high-quality long video grounded QA data, along with a
  corresponding benchmark for systematic evaluation across various video durations. Experimental results
  demonstrate that our method achieves remarkable performance on both long video understanding and grounding.

url_pdf: https://arxiv.org/pdf/2602.07801
url_code: https://github.com/Kwai-Keye/VideoTemp-o3

image:
  focal_point: ""
  preview_only: false
---
