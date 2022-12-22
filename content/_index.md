---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
      design:
        columns: '2'
  - block: experience
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ph.D. in Statistics
          company: Texas A&M University
          company_url: ''
          date_start: '2018-08-02'
          date_end: ''
        - title: M.S. in Statistics
          company: Korea University
          company_url: ''
          date_end: '2018-08-01'
        - title: B.S. in Statistics and B.S. in Economics
          company: Korea University
          company_url: ''
          date_end: '2016-08-01'
    design:
      columns: '2'
  - block: collection
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: jchoi@stat.tamu.edu
      address:
        street: 3143 TAMU
        city: College Station
        region: CA
        postcode: '77843'
        country: United States
        country_code: US
      directions: Office 406F, John R. Blocker Building
    design:
      columns: '2'
---
