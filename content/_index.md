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
    
        - title: Intern
          company: ISE, NUS 
          company_url: 'https://cde.nus.edu.sg/isem/'
          company_logo: NUS
          location: Singapore (Remote)
          date_start: '2022-02-01'
          date_end: '2024-08-01'
          description: |2-
              Supervised by Dr. Haowei Wang.
    
              Research Interests include:

              * Bayesian Optimization.


        - title: Research Assistant
          company: I2R, A*star 
          company_url: 'https://www.a-star.edu.sg/i2r'
          company_logo: astar
          location: Singapore
          date_start: '2023-07-01'
          date_end: '2024-01-01'
          description: |2-
              Supervised by Dr. Xulei Yang.

              Supported by SIPGA scholarship.

              Research Interests include:

              * Semi-supervised algorithm in semiconductor defect detection.
              * 3D machine learning in semiconductor data.

              

    


 
    design:
      columns: '2'

  - block: collection
    id: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: False
    design:
      columns: '2'
      view: citation




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

        - 
          date_end: ''
          date_start: '2024-02-01'
          description: 'Distinguished Graduate of Shanghai'
          organization: Shanghai University
          organization_url: https://sme.shu.edu.cn/index.htm
          title: Distinguished Graduate of Shanghai
          url: https://sme.shu.edu.cn/index.htm
        - 
          date_end: ''
          date_start: '2023-11-01'
          description: 'National Scholarship'
          organization: Ministry of Education
          organization_url: https://sme.shu.edu.cn/info/1030/3802.htm
          title: National Scholarship
          url: https://sme.shu.edu.cn/info/1030/3802.htm
        - 
          date_end: ''
          date_start: '2022-04-01'
          description: ' Rank:5/465'
          organization: Baidu aistudio / Paddle
          organization_url: https://aistudio.baidu.com/
          title: Commercial complex energy consumption forecast
          url: https://aistudio.baidu.com/competition/detail/139/0/introduction
        - 
          date_end: ''
          date_start: '2021-11-01'
          description: 'The second prize'
          organization: CPIPC
          organization_url: https://cpipc.acge.org.cn/cw/hp/4
          title: The 18th China Post-graduated Mathematical Contest In Modeling
          url: 'https://cpipc.acge.org.cn/cw/hp/4'

        - 
          date_end: ''
          date_start: '2020-01-25'
          description: 'Outstanding Winner (Top 0.12%)'
          organization: MCM/ICM
          organization_url: https://www.comap.com/contests/mcm-icm
          title: Mathematical Contest In Modeling
          url: 'https://mcm.njupt.edu.cn/2020/0428/c7019a164407/page.htm'


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
---
