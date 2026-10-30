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
      title: ''
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
      date_format: January 2006
      items:
        - title: Doctoral Research / Research Assistant
          company: Yale University
          company_url: 'https://www.yale.edu/'
          company_logo: yale-logo-blue
          date_start: '2023-09-01'
          date_end: ''

        - title: Research Visit
          company: Northwestern University
          company_url: 'https://www.northwestern.edu/'
          company_logo: northwestern-logo.png
          date_start: '2026-07-01'
          date_end: '2026-09-01'

        - title: Undergraduate Research Assistant
          company: University of Science and Technology of China (USTC)
          company_url: 'https://en.ustc.edu.cn/'
          company_logo: ustc-logo
          date_start: '2021-09-01'
          date_end: '2022-03-01'

        - title: Undergraduate Experimental Project
          company: University of Science and Technology of China (USTC)
          company_url: 'https://en.ustc.edu.cn/'
          company_logo: ustc-logo
          date_start: '2021-09-01'
          date_end: '2021-12-01'
          description: |2-
              First Prize, 17th Physical Innovation Research Experimental Paper Competition, USTC (2021).
    design:
      columns: '2'
  - block: selected_research
    id: research
    content:
      title: Selected Research
    design:
      columns: '1'
  - block: teaching_cards
    id: teaching
    content:
      title: Teaching
      items:
        - title: 'PHYS 1650L: General Physics Laboratory'
          url: 'https://courses.yale.edu/?details&srcdb=202603&crn=12192'
          school: Yale University
          school_url: https://www.yale.edu/
          school_logo: yale-logo-blue.svg
          role: Teaching Assistant
          term: Fall 2026
          instructors: 'Instructors: Sean Barrett, Mehdi Ghiassi-Nejad, Caitlin Hansen, and Alison Sweeney'
        - title: 'EENG 201: Introduction to Computer Engineering'
          url: 'https://courses.yale.edu/?details&srcdb=202501&crn=20234'
          school: Yale University
          school_url: https://www.yale.edu/
          school_logo: yale-logo-blue.svg
          role: Teaching Assistant
          term: Spring 2025
          instructors: 'Instructor: Priya Panda'
        - title: 'EENG 200: Introduction to Electronics'
          url: 'https://courses.yale.edu/?details&srcdb=202403&crn=11113'
          school: Yale University
          school_url: https://www.yale.edu/
          school_logo: yale-logo-blue.svg
          role: Teaching Assistant
          term: Fall 2024
          instructors: 'Instructor: Jung Han'
        - title: Mechanics B
          school: University of Science and Technology of China (USTC)
          school_url: https://en.ustc.edu.cn/
          school_logo: ustc-logo.svg
          role: Undergraduate Teaching Assistant
          term: Fall 2022
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        See the [complete publication list](./publication/), including peer-reviewed papers and preprints.
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
      title: Talks
      archive:
        text: See all talks
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
      title: Awards
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: "2006"
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: ''
          date_start: '2025-10-17'
          description: '[I Know What You Are Reading: Evaluating Readout Crosstalk in Cloud-based Quantum Computers](/publication/qsec2025/)'
          organization: QSec@CCS
          organization_url: https://www.sigsac.org/ccs/CCS2025/events/
          title: Best Paper Award
          url: '/publication/qsec2025/'

        - certificate_url: 
          date_end: ''
          date_start: '2025-04-18'
          description: '[Securing HHL Quantum Algorithm against Quantum Computer Attacks](/publication/hasp2025/)'
          organization: New England Hardware Security Day
          organization_url: https://nehws.org/archive/
          title: Best Poster Award – 1st Place
          url: '/publication/hasp2025/'

        - certificate_url: 
          date_end: ''
          date_start: '2022-01-01'
          date_text: '2022, 2021'
          description: ''
          organization: University of Science and Technology of China
          organization_url: https://en.ustc.edu.cn/
          title: Silver Award of Excellent Student Scholarship (Top 2%)
          url: ''

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
          date_start: '2018-10-01'
          description: ''
          organization: Chinese Physical Society
          organization_url: http://www.cps-net.org.cn/
          title: Provincial First Prize in 35th Chinese Physics Olympiad (CPhO)
          url: ''

    design:
      columns: '2'
  - block: accomplishments
    id: certifications
    content:
      title: Beyond Research
      date_format: "2006"
      sort_by_date: false
      items:
        - title: Meet Beau
          image: community/beau-photo-crop.jpg
          image_alt: Beau
          image_style: portrait
          description_inline: true
          description: >-
            My super friendly cat and self-appointed research supervisor. Whatever I’m doing, he’s convinced it would be better if we did it together.
        - title: Volunteer
          organization: Companion Pet Rescue
          date_text: '2026'
          organization_logo: companion-pet-rescue.png
          organization_url: https://cprdogs.com/
          description: ''
        - certificate_url: 
          date_end: ''
          date_start: '2022-03-31'
          description: ''
          organization: American Heart Association
          organization_logo: american-heart-association.svg
          organization_url: https://www.heart.org/
          title: Basic Life Support (BLS) Provider
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
        street: 51 Prospect Street
        city: New Haven
        region: CT
        postcode: '06511'
        country: United States
        country_code: US
      directions: 5th Floor, Arthur K. Watson Hall (AKW), Yale University
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '41.3130868'
        longitude: '-72.9248501' 
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
