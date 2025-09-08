---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # - block: hero
  #   content:
  #     title: 
  #     image:
  #       filename:
  #     cta:
  #       label: 
  #       url: 
  #     cta_alt:
  #       label: 
  #       url: 
  #     cta_note:
  #       label:        
  #     text: 
  #   design:
  #     background:
  #       gradient_end: 
  #       gradient_start: 
  #       text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    id: experience
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
        # - title: Gen AI Intern
        #   company: Scale AI
        #   company_url: 'https://scale.com/'
        #   company_logo: scale-ai-logo
        #   location: New York, New York
        #   date_start: '2025-06-26'
        #   date_end: ''
        #   description: |2-
        #       Benchmarked generative LLM reasoning on Olympiad-level tasks — conducted research to analyze AI reasoning capabilities, designed experiments to uncover failure modes, and inform model architecture improvements.

        - title: Graduate Research Assistant & Teaching Fellow
          company: Yale University
          company_url: 'https://www.yale.edu/'
          company_logo: yale-logo-blue
          location: New Haven, Connecticut
          date_start: '2023-08-26'
          date_end: ''
          # description: |2-
          #     Responsibilities include:

          #     * Analysing
          #     * Modelling
          #     * Deploying
          description: |2-
              Research Asistant:
              * Member of [Computer Architecture and Security Lab (CASLAB).](https://caslab.io/)
              * Member of [Quantum Systems Lab (QSL).](https://www.yongshanding.com/home.html)

              Teaching Asistant:
              * EENG 200--Introduction to Electronics (Jung Han)
              * EENG 201--Introduction to Computer Engineering (Priya Panda)

        - title: Undergraduate Research Assistant & Teaching Fellow
          company: University of Science and Technology of China (USTC)
          company_url: 'https://en.ustc.edu.cn/'
          company_logo: ustc-logo
          location: Hefei, China
          date_start: '2019-09-01'
          date_end: '2023-05-31'
          description: |2-
              Major in Atomic Physics, Minor in Computer Science

              Teaching Asistant:
              * Mechanics B

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
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
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
  - block: collection
    id: presentations
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: ''
          date_start: '2025-04-28'
          description: 'NEHWS Day brings together many students, researchers, practitioners, and industry partners in the field of hardware security to share their work and foster new ideas.'
          organization: 2025 New England Hardware Security Day
          organization_url: https://nehws.org/
          title: Best Poster Award - 1st Place
          url: ''

        - certificate_url: 
          date_end: ''
          date_start: '2022-03-31'
          description: 'The AHA’s BLS course trains participants to promptly recognize several life-threatening emergencies, give high-quality chest compressions, deliver appropriate ventilations and provide early use of an AED. Reflects science and education from the American Heart Association Guidelines Update for CPR and Emergency Cardiovascular Care (ECC).'
          organization: American Heart Association
          organization_url: https://www.heart.org/
          title: Basic Life Support (BLS) Provider
          url: ''

        # - certificate_url: 
        #   date_end: ''
        #   date_start: '2022'
        #   description: 'Excellent Student Scholarship (10%)'
        #   organization: University of Science and Technology of China
        #   organization_url: https://en.ustc.edu.cn/
        #   title: Silver Award of Excellent Student Scholarship
        #   url: ''  

        - certificate_url: 
          date_end: ''
          date_start: '2021-12-25'
          description: ''
          organization: University of Science and Technology of China
          organization_url: https://en.ustc.edu.cn/
          title: 1st Place in 17th Physical Innovation Research Experimental Paper Competition
          url: ''
        
        - certificate_url: 
          date_end: ''
          date_start: '2020-12-23'
          description: ''
          organization: CUEP
          organization_url: https://cuep.nenu.edu.cn/
          title: Second Prize in 6th China Undergraduate Physics Experiment Competition (CUPEC)
          url: ''

        - certificate_url: 
          date_end: ''
          date_start: '2018-10'
          description: ''
          organization: Chinese Physical Society
          organization_url: http://www.cps-net.org.cn/
          title: Provincial First Prize in 35th Chinese Physics Olympiad (CPhO)
          url: ''

    design:
      columns: '2'
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
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      # subtitle:
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: yizhuo.tan@yale.edu
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: 10 Hillhouse Avenue
        city: New Haven
        region: CT
        postcode: '06520'
        country: United States
        country_code: US
      directions: 5th Floor, Dunham Laboratory
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '41.3123'
        longitude: '-72.9244' 
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
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
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

<!-- <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2996.841158586838!2d-72.9270589242399!3d41.312319000648586!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89e7d9b642fc7fc3%3A0xac0f89b6ff8adee2!2sDunham%20Laboratory%2C%2010%20Hillhouse%20Ave%2C%20New%20Haven%2C%20CT%2006511!5e0!3m2!1sen!2sus!4v1690060037768!5m2!1sen!2sus" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe> -->