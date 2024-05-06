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
  #- block: features
  #  content:
  #    title: Skills
  #    items:
  #      - name: Python
  #        description: 80%
  #        icon: python
  #        icon_pack: fab
  #      - name: Statistics
  #        description: 60%
  #        icon: chart-line
  #        icon_pack: fas
  #      - name: Photography
  #        description: 10%
  #        icon: camera-retro
  #        icon_pack: fas
  - block: experience
    id: experiences
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
        - title: Ph.D. Candidate
          company: Tabaru Lab.
          company_url: 'https://tbr.first.iir.titech.ac.jp/'
          company_logo: titech
          location: Tokyo Institute of Technology
          date_start: '2024-04-01'
          date_end: ''
          description: ''
        - title: Master's Student
          company: Hatsuzawa Lab.
          company_url: 'http://www.hat.first.iir.titech.ac.jp/'
          company_logo: titech
          location: Tokyo Institute of Technology
          date_start: '2022-04-01'
          date_end: '2024-03-31'
          description: ''
        - title: Academic Visitor
          company: Bio-Inspired Robotic Lab.
          company_url: 'https://birlab.org/'
          company_logo: UniCam
          location: University of Cambridge
          date_start: '2022-07-01'
          date_end: '2022-09-30'
          description: ''
        - title: Undergraduate Student
          company: Tokyo Institute of Technology
          company_url: 'https://www.titech.ac.jp/'
          company_logo: titech
          location: Tokyo
          date_start: '2018-04-01'
          date_end: '2022-03-31'
          description: ''
    design:
      columns: '2'
  #- block: accomplishments
  #  content:
  #    # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #    title: 'Accomplish&shy;ments'
  #    subtitle:
  #    # Date format: https://wowchemy.com/docs/customization/#date-format
  #    date_format: Jan 2006
  #    # Accomplishments.
  #    #   Add/remove as many `item` blocks below as you like.
  #    #   `title`, `organization`, and `date_start` are the required parameters.
  #    #   Leave other parameters empty if not required.
  #    #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #    items:
  #      - certificate_url: https://www.coursera.org
  #        date_end: ''
  #        date_start: '2021-01-25'
  #        description: ''
  #        organization: Coursera
  #        organization_url: https://www.coursera.org
  #        title: Neural Networks and Deep Learning
  #        url: ''
  #      - certificate_url: https://www.edx.org
  #        date_end: ''
  #        date_start: '2021-01-01'
  #        description: Formulated informed blockchain models, hypotheses, and use cases.
  #        organization: edX
  #        organization_url: https://www.edx.org
  #        title: Blockchain Fundamentals
  #        url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #      - certificate_url: https://www.datacamp.com
  #        date_end: '2020-12-21'
  #        date_start: '2020-07-01'
  #        description: ''
  #        organization: DataCamp
  #        organization_url: https://www.datacamp.com
  #        title: 'Object-Oriented Programming in R'
  #        url: ''
  #  design:
  #    columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      #buttons:
      #  - name: All
      #    tag: '*'
      #  - name: Deep Learning
      #    tag: Deep Learning
      #  - name: Other
      #    tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: conference
    content:
      title: Conferences
      filters:
        folders:
          - conference
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: featured
    content:
      title: Publications
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
      # Contact (add or remove contact options as necessary)
      email: tano.n.aa@m.titech.ac.jp
      address:
        street: 4259-R2-6, Nagatsuta-cho, Midori-ku
        city: Yokohama city
        region: Kanagawa prefecture
        postcode: '226-8503'
        country: Japan
      #  country_code: US
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      #contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
