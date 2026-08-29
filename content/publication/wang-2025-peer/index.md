---
title: 'PEER: Unified Process-Outcome Reinforcement Learning for Structured Empathetic
  Reasoning'
authors:
- Yunxiao_Wang
- Meng Liu
- Sicheng Zhao
- Lizi Liao
- Liqiang Nie
date: '2025-08-13'
publishDate: '2026-08-24T00:00:00Z'
publication_types:
- manuscript
publication: '*arXiv:2508.09521*'
publication_short: "*arXiv preprint*"

summary: Preprint

abstract: >-
  Emotional support conversations require more than fluent responses. Supporters need to understand the seeker's
  situation and emotions, adopt an appropriate strategy, and respond in a natural, human-like manner. Despite
  advances in large language models, current systems often lack structured, psychology-informed reasoning.
  Additionally, it is challenging to enhance these systems through reinforcement learning because of unreliable
  reward signals. Moreover, reinforcement fine-tuning can amplify repetitive response patterns. We propose
  structured empathetic reasoning, which breaks support into three steps: conversation history analysis,
  multimodal emotional state inference, and strategy selection, prior to generating the final reply. To
  implement this, we introduce SER, a fine-grained dataset with step-level correctness labels and pairwise
  response preferences. We then present PEER, which uses GRPO with UnifiReward, a unified process-outcome reward
  model for evaluating both reasoning steps and final responses in multi-turn interactions. To reduce
  repetition, we enhance data with personality-based rewriting and down-weight redundant outputs. Comprehensive
  experiments show improved empathy, strategy alignment, and human-likeness without sacrificing diversity.

url_pdf: https://arxiv.org/pdf/2508.09521
url_code: https://github.com/Yunxiao-Wang/PEER

image:
  focal_point: ""
  preview_only: false
---
