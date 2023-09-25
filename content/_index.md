---
# Leave the homepage title empty to use the site title
title: Bo
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
        - title: Postdoc
          company: University of Illinois at Urbana-Champaign
          company_url: 'https://illinois.edu/'
          company_logo: org-uiuc
          location: Urbana-Champaign
          date_start: '2022-09-01'
          date_end: ''
        - title: Ph.D.
          company: University of Illinois at Urbana-Champaign
          company_url: 'https://illinois.edu/'
          company_logo: org-uiuc
          location: Urbana-Champaign
          date_start: '2016-09-01'
          date_end: '2022-05-01'
        - title: Student Intern
          company: Meta
          company_url: 'https://www.facebook.com/Meta/'
          company_logo: org-meta
          location: Menlo Park, CA
          date_start: '2020-05-01'
          date_end: '2020-08-01'
        - title: Research Intern
          company: AT&T
          company_url: 'https://www.att.com/'
          company_logo: org-att
          location: Bedminster, NJ
          date_start: '2019-05-01'
          date_end: '2019-07-01'
        - title: Undergraduate
          company: Shanghai Jiao Tong University
          company_url: 'https://www.sjtu.edu.cn/'
          company_logo: org-sjtu
          location: Shanghai, China
          date_start: '2012-09-01'
          date_end: '2016-06-01'
          # description: Taught electronic engineering and researched semiconductor physics.
        - title: High School
          company: Fuzhou No.1 High School
          company_url: 'http://www.fzyz.net/#/'
          company_logo: org-fzyz
          location: Fuzhou, Fujian
          date_start: '2009-09-01'
          date_end: '2012-06-01'
          # description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  - block: collection
    id: featured
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: featured
    content:
      title: Publications/Submissions
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      columns: '2'
      view: list
  - block: collection
    id: awards
    content:
      title: Awards
      filters:
        folders:
          - award
    design:
      columns: '2'
      view: list
  - block: collection
    id: services
    content:
      title: Services
      filters:
        folders:
          - service
    design:
      columns: '2'
      view: list
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
      email: boc2 at illinois dot edu
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # # Automatically link email and phone or display as text?
      # autolink: true
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
