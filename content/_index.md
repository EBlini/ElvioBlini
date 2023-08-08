---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
# - block: features
#   content:
#     items:
#     - description: 90%
#       icon: r-project
#       icon_pack: fab
#       name: R
#     - description: 100%
#       icon: chart-line
#       icon_pack: fas
#       name: Statistics
#     - description: 10%
#       icon: camera-retro
#       icon_pack: fas
#       name: Photography
#     title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: University of Florence
      company_logo: Logo_unifi
      company_url: ""
      date_end: ""
      date_start: "2023-01-15"
      # description: |2-
      #     Responsibilities include:
      # 
      #     * Analysing
      #     * Modelling
      #     * Deploying
      location: Firenze, ITA
      title: Assistant Professor (RTDa)
    - company: University of Padua
      company_logo: Logo_unipd
      company_url: ""
      date_end: "2022-05-15"
      date_start: "2020-05-15"
      location: Padova, ITA
      title: Senior Postdoc Fellow (type B)
    - company: INSERM (Institut national de la santé et de la recherche médicale)
      company_logo: Logo_inserm
      company_url: ""
      date_end: "2020-02-15"
      date_start: "2018-02-15"
      location: Lyon, FRA
      title: Marie Skłodowska Curie Research Fellow
    - company: University of Lyon
      company_logo: Logo_ul
      company_url: ""
      date_end: "2018-02-15"
      date_start: "2016-06-15"
      location: Lyon, FRA
      title: PRESTIGE, Marie Skłodowska Curie Research Fellow
  #   - company: University X
  #     company_logo: org-x
  #     company_url: ""
  #     date_end: "2020-12-31"
  #     date_start: "2016-01-01"
  #     description: Taught electronic engineering and researched semiconductor physics.
  #     location: California
  #     title: Professor of Semiconductor Physics
  #   title: Experience
  # design:
  #   columns: "2"
# - block: accomplishments
#   content:
#     date_format: Jan 2006
#     items:
#     - certificate_url: https://www.coursera.org
#       date_end: ""
#       date_start: "2021-01-25"
#       description: ""
#       organization: Coursera
#       organization_url: https://www.coursera.org
#       title: Neural Networks and Deep Learning
#       url: ""
#     - certificate_url: https://www.edx.org
#       date_end: ""
#       date_start: "2021-01-01"
#       description: Formulated informed blockchain models, hypotheses, and use cases.
#       organization: edX
#       organization_url: https://www.edx.org
#       title: Blockchain Fundamentals
#       url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#     - certificate_url: https://www.datacamp.com
#       date_end: "2020-12-21"
#       date_start: "2020-07-01"
#       description: ""
#       organization: DataCamp
#       organization_url: https://www.datacamp.com
#       title: Object-Oriented Programming in R
#       url: ""
#     subtitle: null
#     title: Accomplish&shy;ments
#   design:
#     columns: "2"
- block: collection
  content:
    count: 2
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: FCnet
      tag: FCnet
    - name: Pupilla
      tag: Pupilla
    # - name: Other
    #   tag: Other
    default_button_index: 2
    filters:
      folders:
      - project
      title: Projects
  design:
    count: 1
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
# - block: markdown
#   content:
#     subtitle: ""
#     text: '{{< gallery album="demo" >}}'
#     title: Gallery
#   design:
#     columns: "1"
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks
- block: collection
  content:
    count: 1
    date_format: 2006
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    count: 1
    date_format: 2006
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
- block: contact
  content:
    address:
      city: Firenze
      country: Italia
      country_code: IT
      postcode: "50135"
      region: Toscana
      street: via di San Salvi 12, edificio 26
    #appointment_url: https://calendly.com
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/e_blini
      name: DM Me
    # - icon: skype
    #   icon_pack: fab
    #   link: skype:echo123?call
    #   name: Skype Me
    # - icon: video
    #   icon_pack: fas
    #   link: https://zoom.com
    #   name: Zoom Me
    #directions: Only on appointment by email.
    email: elvioadalberto.blini@unifi.it
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    # office_hours:
    # - Monday 10:00 to 13:00
    # - Wednesday 09:00 to 10:00
    # phone: 888 888 88 88
    # subtitle: null
    text: 
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
