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
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: 80%
          icon: python
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: C++
          description: 60%
          icon: code
          icon_pack: fas
  - block: experience
    content:
      title: Educational Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Bachelor's Degree of Material Science and Engineering
          company: Xi'an Jiaotong University
          company_url: ''
          company_logo: org-xjtu
          location: Xi'an, China
          date_start: '2015-09-01'
          date_end: '2019-08-31'
          description: Majored in Metal Material & Energy Nano Materials.
        - title: Bachelor's Degree of Finance
          company: Xi'an Jiaotong University
          company_url: ''
          company_logo: org-xjtu
          location: Xi'an, China
          date_start: '2015-09-01'
          date_end: '2019-08-31'
          description: Majored in Commercial Bank Assets Analysis.
        - title: Program on Introduction to Data Science
          company: Harvard University
          company_url: ''
          company_logo: org-HV
          location: Boston, MA, USA
          date_start: '2019-10-12'
          date_end: '2019-11-27'
          description: Supervised by Prof. Pavlas Protopapas from Institute for Applied Computational Science, Harvard University, and recognized for successful completion of the 2019 Online Project-Based Program on Introduction to Data Science.
        - title: PhD Degree of Control Science and Engineering
          company: Xi'an Jiaotong University
          company_url: ''
          company_logo: org-xjtu
          location: Xi'an, China
          date_start: '2019-09-01'
          date_end: ''
          description: Currently persuing PhD degree.
    design:
      columns: '4'
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
      buttons:
        - name: All
          tag: '*'
        - name: Shared Mental Model
          tag: Shared Mental Model
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: publication
    content:
      title: Recent Publications
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
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Contact me for cooperation, discussion and offer of other opportunities!
      # Contact (add or remove contact options as necessary)
      email: marsroscope@stu.xjtu.edu.cn
      phone: +86 153 1945 2189
      address:
        street: 28 Xianningxilu Street
        city: Xi'an
        region: Shaanxi
        postcode: '710000'
        country: China
        country_code: CN
      directions: Pengkang Building 2nd floor.
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
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
