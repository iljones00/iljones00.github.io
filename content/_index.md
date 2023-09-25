---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
    # design:
    #   background:
    #     gradient_end: '#1976d2'
    #     gradient_start: '#004ba0'
    #     text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
        - title: AI Research Scientist
          company: Peraton Labs
          company_url: 'https://www.peratonlabs.com/'
          # company_logo: peraton_labs
          location: Basking Ridge, NJ
          date_start: '2023-03-22'
          date_end: ''
          description: |2-
            * Building AI proof of concepts and machine learning models on drones for object avoidance
            * Automating government and military system testing facilities
        - title: AI Research Intern
          company: Fermilab
          company_url: 'https://www.fnal.gov/'
          # company_logo: fermi
          location: Batavia, IL
          date_start: '2022-06-15'
          date_end: '2022-12-15'
          description: |2-
            * Investigated and tested various neural network architectures aimed to disentangle beam loss monitor readings between main injector and recycler accelerators.
            * Designed and tested various models (Multilayer Perceptron, U-Net, RNNs) with Keras and PyTorch
            * Constructed a ML pipelines that automates the cycle of extracting data from a data source, cleaning and processing the data, transferring the data to the cloud, training a model on the cloud, and then evaluating/validating the model.
            * Performed hyperparameter tuning to improve upon model efficiency and performance metrics
        - title: Quant Research Intern
          company: Chicago Global
          company_url: 'https://chicago.global/'
          # company_logo: chicago_global
          location: Singapore
          date_start: '2016-01-01'
          date_end: '2020-12-31'
          description: |2-
            * Developed and implemented successful investment strategies by replicating research papers utilizing alternative data.
            * Optimized a methods to analyze market sentiment and help portfolio manager systematically adjust hedge ratios
            * Performed time-series analysis on 30,000+ stock dataset to improve internal risk factors and other measurements of value and profitability
        - title: Software Engineering Intern
          company: Cydeas
          company_url: 'https://cydeas.com/'
          # company_logo: cydeas
          location: Hong Kong
          date_start: '2016-01-01'
          date_end: '2020-12-31'
          description: |2-
            * Developed back-end infrastructure and RESTful APIs for web applications in Clojure deployed in the cloud
            * Managed several SQL server databases (Postgres) to support the delivery of data in real-time for sales conversions

    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplishments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.udemy.com/certificate/UC-ad36e1d5-1a8a-414f-8f71-5c88850aa5aa
          date_end: ''
          date_start: '2022-03-01'
          description: 'Machine learning for medical image manipulation and analysis'
          organization: Udemy
          organization_url: https://www.udemy.com
          title: Deep Learning with PyTorch for Medical Image Analysis
          url: ''
        - certificate_url: https://www.udemy.com/certificate/UC-5b2d264d-c695-4446-91bb-b4b0e27bf21a
          date_end: ''
          date_start: '2021-08-01'
          description: 'Extensive dive into theory and application of various ML model architectures'
          organization: Udemy
          organization_url: https://www.udemy.com
          title: Machine Learning A-Z - Hands-On Python & R in Data Science
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/M68BUCHHFTQH
          date_end: ''
          date_start: '2020-08-01'
          description: 'Database interfacing with SQL'
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Introduction to Structured Query Langauge (SQL)
          url: ''
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
