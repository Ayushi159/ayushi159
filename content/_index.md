---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about

- block: accomplishments
  content:
    # filters:
    #   exclude_featured: false
    #   folders:
    #   - publication
    # text: |-
    #   {{% callout note %}}
    #   Quickly discover relevant content by [filtering publications](./publication/).
    #   {{% /callout %}}
    title: Publications
    items:
    - certificate_url: 
      date_end: ""
      date_start: "2019-07-25"
      description: Awarded Vice-Chancellor Gold Medal by N.R.Narayana Murthy and Chief Minister Yogi Adityanath for holding 1st Rank in Computer Science Department.
      organization: MMMUT
      organization_url:
      title: 
      url: ""
  design:
    columns: "2"
    view: citation
  id: featured
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: GenCoin
      company_logo: org-gc
      company_url: ""
      date_end: ""
      date_start: "2021-01-01"
      description: |2-
          Responsibilities include:

          * Analysing
          * Modelling
          * Deploying
      location: California
      title: CEO
    - company: University X
      company_logo: org-x
      company_url: ""
      date_end: "2020-12-31"
      date_start: "2016-01-01"
      description: Taught electronic engineering and researched semiconductor physics.
      location: California
      title: Professor of Semiconductor Physics
    title: Experience
  design:
    columns: "2"
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: 
      date_end: ""
      date_start: "2019-07-25"
      description: Awarded Vice-Chancellor Gold Medal by N.R.Narayana Murthy and Chief Minister Yogi Adityanath for holding 1st Rank in Computer Science Department.
      organization: MMMUT
      organization_url:
      title: 
      url: ""
    - certificate_url: 
      date_end: ""
      date_start: "2019-07-01"
      description: Awarded Sponsored Gold Medal(Shri Munni Lal Jain Memorial Gold Medal) in the Computer Science and Engineering Department
      organization: MMMUT
      organization_url: 
      title:
      url: ""
    - certificate_url: 
      date_end: ""
      date_start: "2018-07-01"
      description: Awarded Malaviyan Excellent Student Award(MESA) for outstanding academic performance
      organization: MMMUT
      organization_url: 
      url: ""
    - certificate_url: 
      date_end: ""
      date_start: "2018-07-01"
      description: Certificate of Merit for 1st position in B.Tech 1st Year in Computer Science Department
      organization: MMMUT
      organization_url: 
      title:
      url: ""
    - certificate_url: 
      date_end: ""
      date_start: "2020-07-01"
      description: Participated in ACM India Grad Cohort for women in computing, organized by IIT Gandhinagar
      organization: ACM Grad Cohort
      organization_url: 
      title:
      url: ""
    - certificate_url: 
      date_end: ""
      date_start: "2023-01-01"
      description: COMSNETS 2023 Travel Grant Awardee
      organization: COMSNETS
      organization_url: 
      title:
      url: ""
    - certificate_url: 
      date_end: ""
      date_start: "2021-07-01"
      description: Shortlisted for participating in Maitreyee, An IBM Research-India’s annual women outreach event
      organization: IBM Research
      organization_url: 
      title:
      url: ""
    subtitle: null
    title: Awards and Honors
  design:
    columns: "2"
# - block: collection
#   content:
#     count: 5
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - post
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: Recent Posts
#   design:
#     columns: "2"
#     view: compact
#   id: posts
# - block: portfolio
#   content:
#     buttons:
#     - name: All
#       tag: '*'
#     - name: Deep Learning
#       tag: Deep Learning
#     - name: Other
#       tag: Demo
#     default_button_index: 0
#     filters:
#       folders:
#       - project
#     title: Projects
#   design:
#     columns: "1"
#     flip_alt_rows: false
#     view: showcase
#   id: projects
# - block: markdown
#   content:
#     subtitle: ""
#     text: '{{< gallery album="demo" >}}'
#     title: Gallery
#   design:
#     columns: "1"
# - block: collection
#   content:
#     filters:
#       featured_only: true
#       folders:
#       - publication
#     title: Featured Publications
#   design:
#     columns: "2"
#     view: card
#   id: featured
# - block: collection
#   content:
#     filters:
#       exclude_featured: false
#       folders:
#       - publication
#     text: |-
#       {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#       {{% /callout %}}
#     title: Recent Publications
#   design:
#     columns: "2"
#     view: citation
#   id: featured
# - block: collection
#   content:
#     filters:
#       folders:
#       - event
#     title: Recent & Upcoming Talks
#   design:
#     columns: "2"
#     view: compact
#   id: talks
# - block: tag_cloud
#   content:
#     title: Popular Topics
#   design:
#     columns: "2"
- block: contact
  content:
    address:
      city: Stanford
      country: United States
      country_code: US
      postcode: "94305"
      region: CA
      street: 450 Serra Mall
    appointment_url: https://calendly.com
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/Twitter
      name: DM Me
    - icon: skype
      icon_pack: fab
      link: skype:echo123?call
      name: Skype Me
    - icon: video
      icon_pack: fas
      link: https://zoom.com
      name: Zoom Me
    directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: test@example.org
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    - Monday 10:00 to 13:00
    - Wednesday 09:00 to 10:00
    phone: 888 888 88 88
    subtitle: null
    text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
      ut magna et, vehicula efficitur enim.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
