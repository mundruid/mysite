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
        - description: 
          icon: lock
          icon_pack: fas
          name: Network Security
        - description:  
          icon: python
          icon_pack: fab
          name: Python
        - description: 
          icon: chart-line
          icon_pack: fas
          name: Machine Learning
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
        - title: Senior Security Researcher
          company: Cyber adAPT
          company_url: 'https://www.cyberadapt.com/'
          company_logo: 
          location: Texas
          date_start: '2022-08-15'
          date_end: ''
          description: |2-
              Responsibilities include:
        
              * Research in Network Security and IoT
              * Development of machine learning PoCs with security applications 
              * Research in intrusion detection
        - title: Senior Consultant 
          company: Network to Code
          company_url: ''
          company_logo: 
          location: New York
          date_start: '2020-05-04'
          date_end: '2022-08-14'
          description: |2-
              Responsibilities include:
              
              * Develop software for network automation workflows
              * Create CI/CD pipelines
              * Telemetry
        
        - title: Assistant Professor of Computer Science
          company: College of Charleston
          company_url: ''
          company_logo: 
          location: Charleston
          date_start: '2016-08-30'
          date_end: '2020-05-03'
          description: Taught computer security, data structures, and software engineering. Research in network security.
    design:
      columns: '2'
  - block: accomplishments
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
        # - certificate_url: https://developer.cisco.com/
        # date_end: "2024-07-15"
        # date_start: "2021-07-15"
        # description: ""
        # organization: Cisco
        # organization_url: https://www.cisco.com/
        # title: Cisco Certified DevNet Specialist - Core
        # url: ""
        # - certificate_url: https://developer.cisco.com/
        # date_end: "2020-07-15"
        # date_start: "2023-07-15"
        # description: ""
        # organization: Cisco
        # organization_url: https://www.cisco.com/
        # title: Cisco Certified DevNet Associate
        # url: ""
        # - certificate_url: https://www.redhat.com/en/services/certification/red-hat-certified-specialist-in-ansible-network-automation
        # date_end: "2022-08-01"
        # date_start: "2020-08-01"
        # description: ""
        # organization: Red Hat
        # organization_url: https://www.redhat.com/en
        # title: 'Red Hat Delivery Specialist - Automation'
        # url: ""
        - certificate_url: https://developer.cisco.com/
          date_end: "2024-07-15"
          date_start: "2021-07-15"
          description: ""
          organization: Cisco
          organization_url: https://www.cisco.com/
          title: Cisco Certified DevNet Specialist - Core
          url: ""
        - certificate_url: https://developer.cisco.com/
          date_end: "2020-07-15"
          date_start: "2023-07-15"
          description: ""
          organization: Cisco
          organization_url: https://www.cisco.com/
          title: Cisco Certified DevNet Associate
          url: ""
        - certificate_url: https://www.redhat.com/en/services/certification/red-hat-certified-specialist-in-ansible-network-automation
          date_end: "2022-08-01"
          date_start: "2020-08-01"
          description: ""
          organization: Red Hat
          organization_url: https://www.redhat.com/en
          title: 'Red Hat Delivery Specialist - Automation'
          url: ""
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
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
      buttons:
        - name: All
          tag: '*'
        - name: Network Security 
          tag: Network Security
        - name: Machine Learning
          tag: Machine Learning
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
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
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      email: xenia.mountrouidou@gmail.com
      address:
        city: Charleston
        region: SC
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true

    design:
      columns: '2'
---
