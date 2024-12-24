---
# Leave the homepage title empty to use the site title
title: ""
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: routing.png
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: News
    content:
      title: ''
      subtitle: ''
      text: |-
       {{% callout note %}}
        Hiring PhD student to work on Graph Neural Network in Fall 2025. Fill [**this form**](https://docs.google.com/forms/d/e/1FAIpQLSfn6kMO-Wleb7R2NJLsJsbTc5N7gX1r4hx5oZacs2Od-rGUEA/viewform?usp=send_form) to apply.
        {{% /callout %}}

        * 10/24 Tutorial Session at [**SIAM MDS 24'**](https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=80791)
        * 10/24 Tutorial Session at [**CIKM 24'**](https://cikm2024.org/tutorials/) 
        * 6/24: Check our **[CVPR 24'](https://cvpr.thecvf.com/virtual/2024/tutorial/23726)** tutorial on <u>Unifying Spectral and Spatial Graph Neural Network</u>. See the tutorial website [CVPR 24' Tutorial](https://xgraph.team/course/cvpr24/).
        * 08/24: Joined the Computer Science Department of Northern Illinois University
    design:
      columns: '1'
  - block: markdown
    content:
      title: '♾️ My Research'
      subtitle: ''
      text: |-
        - Graph Neural Network for Combinatorial Optimization: Can GNNs perform reasoning and tackle (NP-hard) mathematical problems that traditional algorithms usually solve?
        - Scalable Graph Structure Learning (GSL): GSL often has high time complexity due to the need to compute pairwise node correlations. Can we reduce this time complexity?
        - Gradient-based Neural Architecture Search: Neural network architectures can be represented as graph structures. Can graph neural networks learn the distribution and patterns of these architectures in graph form and generate optimal ones?  
        - Graph Neural Network for Science: For problems that AI has not yet solved, is it possible to formulate them as graph-based challenges and apply GNNs to find solutions?
        - Graph Neural Network Theory: How to bridge the gap between the spatial and spectral graph neural networks? What are the theoretical guarantees of them? 

        Please reach out to collaborate 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 📌Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: 📋Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: 📢Recent Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: markdown
    id: trivia
    content:
      title: '🤖Trivia'
      subtitle: ''
      text: |-
        - [An Autobiography](/autobiography/)
        - My hobbies 
    design:
      columns: '1'
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
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
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
