---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD Student
          company: Beijing Institute of Technology
          company_url: ''
          company_logo: bit
          location: Beijing
          date_start: '2022-08-26'
          date_end: ''
          description: ''
        - title: Java Programer
          company: Beijing Institute of Technology Southeast Institute of Information Technology
          company_url: ''
          company_logo: bit
          location: Putian
          date_start: '2021-07-01'
          date_end: '2022-07-01'
          description: |2-
              Responsibilities include:

              * Java Develop
              * Vue Develop
              * Deploying
        - title: Master Student
          company: Beijing Information Science and Technology University
          company_url: ''
          company_logo: bistu
          location: Beijing
          date_start: '2018-09-01'
          date_end: '2021-06-30'
          description: ''
        - title: Bachelor Student
          company: Beijing Information Science and Technology University
          company_url: ''
          company_logo: bistu
          location: Beijing
          date_start: '2014-09-01'
          date_end: '2018-06-30'
          description: ''
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: citation
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
  #     email: test@example.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'
---
