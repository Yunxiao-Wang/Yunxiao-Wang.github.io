---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: Yunxiao_Wang
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Visiting Research Student
          company: CoAgent Lab, Singapore Management University
          company_url: ''
          company_logo: org-gc
          location: Singapore
          date_start: '2026-02-26'
          date_end: ''
          description: I work on conversational personality assessment, and on [KakiPal](https://www.kakipal.com/), an AI learning companion that pairs Socratic tutoring with camera-free affect sensing. KakiPal is in production and in use in university teaching.
        - title: Research Intern
          company: Foundation Model & Applications Department, Kuaishou Technology
          company_url: ''
          company_logo: org-x
          location: Beijing, China
          date_start: '2024-07-01'
          date_end: '2025-12-31'
          description: I worked on video large language models, covering temporal-sensitive instruction tuning with a shortcut-filtered benchmark for temporal understanding (AAAI 2026, Oral), and an agentic thinking-with-videos framework that unifies temporal grounding with question answering (ICML 2026).
        - title: Lightweight Detection of Hidden Dangers in Transmission Line
          company: Member, Cooperation Project with Zhiyang Innovation Technology Co., Ltd.
          company_url: ''
          company_logo: org-xx
          location: Qingdao, China
          date_start: '2019-06-01'
          date_end: '2020-02-01'
          description: I built a lightweight detector for transmission-line inspection, pairing ShuffleNet and MobileNet feature extractors with a Faster R-CNN framework.
        - title: Product Nameplate Text Recognition
          company: Data Analysis Intern, Weichai Power Co., LTD
          company_url: ''
          company_logo: org-xxx
          location: Weifang, China
          date_start: '2018-10-01'
          date_end: '2019-05-31'
          description: I detected and recognised irregularly arranged text on product nameplates with EAST and CTPN detection and CRNN recognition, automating product-information entry.
    design:
      columns: '2'
  - block: collection
    id: publication
    content:
      title: Publications
      # Show all publications rather than the default five
      count: 0
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: compact
  - block: markdown
    id: patents
    content:
      title: Patents & Standards
      text: |2-
         Chinese invention patents:
         - CN113590881B — Video clip retrieval and retrieval-model training
         - CN117271743B — Multimodal dialogue emotion recognition
         - CN118898797B — Commonsense-enhanced candidate generation for video action segments
         - CN119670896B — Temporally enhanced video question answering
         - CN120747839B — User behaviour prediction for smart homes
         - CN120805980A — Quantized multimedia question answering for smart-home edge devices (under examination)

         Standards, as a co-drafter:
         - SJ/T 12100-2026 — Industrial AI vision online inspection systems for the power industry (industry standard, 2026)
         - T/CESA 1298-2023 / T/CES 247-2023 — Industrial AI vision online inspection systems for transmission lines (group standard, 2023)
    design:
      columns: '2'
  - block: markdown
    id: services
    content:
      title: Professional Services
      text: |2-
         Conference reviewer for:
         - AAAI Conference on Artificial Intelligence (AAAI)
         - ACM International Conference on Multimedia (ACM MM)
         - Annual Meeting of the Association for Computational Linguistics (ACL)
         - Conference on Neural Information Processing Systems (NeurIPS)

         Journal reviewer for:
         - IEEE Transactions on Knowledge and Data Engineering
         - IEEE Transactions on Circuits and Systems for Video Technology
         - IEEE Transactions on Multimedia
         - Information Sciences
    design:
      columns: '2'
  - block: markdown
    id: awards
    content:
      title: Honors & Awards
      text: |2-
         - First Prize of Graduate Academic Scholarship (2023)
         - Second Prize of Graduate Freshmen Scholarship (2022)
         - Third Prize of Graduate Academic Scholarship (2020-2021)
         - First Prize of Graduate Freshmen Scholarship (2019)
         - Excellent Graduate of China University of Petroleum (East China) (2019)
         - National Second Prize of the 14th "Bochuang" Cup National College Students Embedded Design Competition (2018)
         - Third Prize of the 13th National College Students "NXP" Cup Intelligent Car Competition in Shandong Region (2018)
         - First Prize of Academic Scholarship (2018)
         - First Prize of the 12th National College Students "NXP" Cup Intelligent Car Competition in Shandong Region (2017)
         - Second Prize of the 15th Shandong University Students Software Design Competition (2017)
         - "Outstanding Achievements in Scientific and Technological Contributions" Scholarship (2017)
         - Third Prize of Academic Scholarship (2017)
         - "Shengli Oil Talent" Scholarship (2016)
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: yunxiao.wang@mail.sdu.edu.cn
      address:
        street: 1500 ShunHua Road, High Tech Industrial Development Zone
        region: Shandong
        city: Jinan
        postcode: '250101'
        country: China
        country_code: CN
      autolink: true
    design:
      columns: '2'
---
