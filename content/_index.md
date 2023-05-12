---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: 
    username: admin
  id: about
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: University of Minnesota
      company_logo: UMN-Logo
      date_end: ""
      date_start: "2020-09-01"
      description: ""
      location: Twin Cities
      title: PhD | Psychological Foundations of Education 
    - company: University of Minnesota
      company_logo: UMN-Logo
      date_end: "2019-05-01"
      date_start: "2016-09-01"
      description: ""
      location: Twin Cities
      title: BA | Developmental Psychology
    title: Education
  design:
    columns: "2"
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
- block: collection
  content:
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
- block: contact
  content:
    address:
      city: Minneapolis
      country: United States
      country_code: US
      postcode: "55455"
      region: MN
      street: 56 E River Rd
    autolink: true
    email: bulla049@umn.edu
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
