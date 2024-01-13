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
        - title: Product Nameplate Text Recognition 
          company: Data Analysis Intern, Weichai Power Co., LTD
          # company_url: 'https://www.weichaipower.com/'
          #company_logo: number-1
          location: Weifang, China
          date_start: '2018-10-01'
          date_end: '2019-05-31'
          description: My task is to automatically input product information by utilizing natural scene text detection models like EAST, CTPN, and text recognition models like CRNN to detect and identify irregularly arranged words on the product nameplate.
        - title: Lightweight Detection of Hidden Dangers in Transmission Line
          company: Project Team Member, Shanda-Zhiyang Joint Laboratory
          company_url: ''
          #company_logo: number-2
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
      view: compact
  - block: markdown
    id: services
    content:
      title: Professional Services
      text: |2-
         Reviewer for:
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
      phone: +86 15621387188
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
