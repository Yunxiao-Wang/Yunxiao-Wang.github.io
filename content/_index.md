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
      username: Yunxiao Wang
  - block: experience
    content:
      title: Project Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Product Nameplate Text Recognition (Weichai Power Co., LTD)
          company: Data Analysis Intern, Big Data Department
          company_url: 'https://www.weichaipower.com/'
          # company_logo: org-gc
          location: Weifang, China
          date_start: '2018-10-01'
          date_end: '2019-05-31'
          description: My task is to automatically input product information by utilizing natural scene text detection models like EAST, CTPN, and text recognition models like CRNN to detect and identify irregularly arranged words on the product nameplate.
        - title: Lightweight Detection of Hidden Dangers in Transmission Line (Shanda-Zhiyang Joint Laboratory)
          company: Project Team Member
          company_url: ''
          # company_logo: org-x
          location: Qiangdao, China
          date_start: '2019-06-01'
          date_end: '2020-02-01'
          description: My task is to detect hidden dangers in transmission lines by utilizing lightweight convolutional neural networks such as ShuffleNet and MobileNet, as well as object detection models like Faster R-CNN.
    design:
      columns: '2'
  - block: collection
    id: publication
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: awards
    content:
      title: Honors & Awards
      text: sdsdsdsdsd
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: yunxiao.wang@mail.sdu.edu.cn
      phone: +86 15621387188
      address:
        street: 1500 ShunHua Road
        region: High Tech Industrial Development Zone
        city: Jinan
        postcode: '250101'
        country: China
        country_code: CN
      autolink: true
    design:
      columns: '2'
---
