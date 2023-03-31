---
# Leave the homepage title empty to use the site title
title:
date: 2022-11-28
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      #text:
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Student Researcher
          company: Advisors Haiyan Huang and Lexin Li
          company_url: ''
          company_logo:
          location: Berkeley, CA
          date_start: '2021-06-01'
          date_end: ''
          description: |2-
              Current goals of research:

              * Develop integrative machine learning methods to study multi-omics sequencing and cancer cell line drug response data.
              * Develop reinforcement learning methods for neurology problems.
        - title: Environmental Health Sciences Graduate Student Assistant
          company: Remais Lab
          company_url: 'https://justinremais.weebly.com'
          company_logo:
          location: Berkeley, CA
          date_start: '2020-06-01'
          date_end: '2021-08-31'
          description: Researched and developed R modules to apply optimization methods useful for assorted problem contexts arising in infectious disease modeling. Created and gave instructional presentations of optimization topics for the research team.
        - title: Research Analyst
          company: The Brattle Group
          company_url: 'https://www.brattle.com'
          company_logo:
          location: Boston, MA
          date_start: '2017-07-01'
          date_end: '2019-06-01'
          description: |2-

              * Collaborated in a small modeling team to accurately estimate financial damages resulting from anticompetitive practices in large scale healthcare antitrust case.
              * Cleaned and transformed high-dimensional healthcare utilization data, performed exploratory analysis on utilization compositions across insurers, specified and tuned a zero-inflated model to predict individual expected healthcare costs.
              * Scraped and compiled hospital data, discharge data, and insurance data to help construct multinomial response models of hospital choice and insurance plan choice.
    design:
      columns: '2'
  - block: markdown
    id: teaching
    content:
      title: Teaching Experience
      subtitle: ''
      text: |2-
        **University of California, Berkeley (Acting Professor):**

        * STAT 151A: Linear Modeling: Theory and Applications (Spring 2023)


        **University of California, Berkeley (Teaching Assistant):**

        * DATA C102: Data, Inference, and Decisions (Fall 2022)
        * PB HLTH 241: Statistical Analysis of Categorical Data (Spring 2021)
        * PB HLTH 142: Introduction to Statistics in Public Health (Spring 2020)
        * PB HLTH 142: Introduction to Statistics in Public Health (Fall 2019)

        **The Brattle Group:**

        * Taught fundamentals of casework analysis and presentation (Fall 2018)

        **Great service organizations** (Org | Task | Location | Time)

        * Cal BASIS Program | Youth science presentations | East Bay, CA | 2021-2022
        * Berkeley Scholars to Cal | Tutoring | East Bay, CA | 2020-2021
        * Tutoring Plus Cambridge | Tutoring | Cambridge, MA | 2017-2019
        * Supplies for Dreams | Mentoring | Chicago, IL | 2016-2017
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
  #- block: collection
  #  id: posts
  #  content:
  #    title: Recent Posts
  #    subtitle: ''
  #    text: ''
  #    # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
  #    # Filter on criteria
  #    filters:
  #      folders:
  #        - post
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
  #    # Choose how many pages you would like to offset by
  #    offset: 0
  #    # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
  #    # Choose a layout view
  #    view: compact
  #    columns: '2'
  #- block: portfolio
  #  id: projects
  #  content:
  #    title: Projects
  #    filters:
  #      folders:
  #        - project
  #    # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #    default_button_index: 0
  #    # Filter toolbar (optional).
  #    # Add or remove as many filters (`filter_button` instances) as you like.
  #    # To show all items, set `tag` to "*".
  #    # To filter by a specific tag, set `tag` to an existing tag name.
  #    # To remove the toolbar, delete the entire `filter_button` block.
  #    buttons:
  #      - name: All
  #        tag: '*'
  #      - name: Deep Learning
  #        tag: Deep Learning
  #      - name: Other
  #        tag: Demo
  #  design:
  #    # Choose how many columns the section has. Valid values: '1' or '2'.
  #    columns: '1'
  #    view: showcase
  #    # For Showcase view, flip alternate rows?
  #    flip_alt_rows: false
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
        #exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: dogtime
    content:
      title: Some highlights of Solo the Dog
      subtitle: ''
      text: |-
        {{< gallery album="solo" >}}
    design:
      columns: '1'
  #- block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card

  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
  #- block: contact
  #  id: contact
  #  content:
  #    title: Contact
  #    subtitle:
  #    text: |-
  #      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #    # Contact (add or remove contact options as necessary)
  #    email: test@example.org
  #    phone: 888 888 88 88
  #    appointment_url: 'https://calendly.com'
  #    address:
  #      street: 450 Serra Mall
  #      city: Stanford
  #      region: CA
  #      postcode: '94305'
  #      country: United States
  #      country_code: US
  #    directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #    office_hours:
  #      - 'Monday 10:00 to 13:00'
  #      - 'Wednesday 09:00 to 10:00'
  #    contact_links:
  #      - icon: twitter
  #        icon_pack: fab
  #        name: DM Me
  #        link: 'https://twitter.com/Twitter'
  #      - icon: skype
  #        icon_pack: fab
  #        name: Skype Me
  #        link: 'skype:echo123?call'
  #      - icon: video
  #        icon_pack: fas
  #        name: Zoom Me
  #        link: 'https://zoom.com'
  #    # Automatically link email and phone or display as text?
  #    autolink: true
  #    # Email form provider
  #    form:
  #      provider: netlify
  #      formspree:
  #        id:
  #      netlify:
  #        # Enable CAPTCHA challenge to reduce spam?
  #        captcha: false
  #  design:
  #    columns: '2'
---
