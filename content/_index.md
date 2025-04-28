---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
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
      # # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    id: news
    content:
      title: 'Recent News'
      text: |-
        **[2025/01]** Defended my Ph.D. degree. 🎓  
        
        **[2025/01]** Received the **Excellent Report Award** at the **2nd National Environmental Postdoctoral Forum**. 🏆  

        **[2023/01]** Started my **Visiting Ph.D. Student** program at **King’s College London**. 📍 

        **[2023/08]** Awarded **Second Prize** in the **5th National Competition in Science & Technology on Renewable Energy for College Students**. 🏆  

        **[2023/07]** Paper **"Residents' willingness to pay for renewable electricity"** accepted in *Journal of Cleaner Production*. 📄  

        **[2022/10]** Awarded **First Prize** in the **"Jijia Cup" Intellectual Property Science Popularization Pioneer Competition**. 🏆  

        **[2022/06]** Paper **"Economic environmental imbalance in China"** accepted in *Journal of Environmental Management*. 📄  

        **[2022/05]** Paper **"Critical supply chains of NOx emissions"** accepted in *Journal of Cleaner Production*. 📄  

        **[2022/04]** Paper **"A bibliometrics review of hotspots in water footprint research"** accepted in *Frontiers in Environmental Science*. 📄  

        **[2021/10]** Started as a **Guest Researcher** in **Zhu Liu’s Research Group (Carbon Monitor) at Tsinghua University**. 📍  

        **[2021/10]** Awarded **Third Prize** in the **14th "Challenge Cup" Academic Science and Technology Works Competition** at **Tianjin University**. 🏆  

        **[2021/07]** Awarded **Third Prize** in the **7th National College Students Academic Creativity Competition on Energy Economy**. 🏆  

        **[2020/09]** Awarded **Silver Award** in the **2nd National College Student Sports Industry Innovation and Entrepreneurship Competition**. 🏆  

        **[2019/10]** Awarded **First-class Academic Scholarship**. 🏆 

        **[2019/08]** Enrolled as a Ph.D. student at **Tianjin University**. 🏫 

        **[2016/12]** Awarded **National Scholarship**. 🏆  

    design:
      columns: '1'
  
  - block: markdown
    id: research
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
        Please reach out to collaborate 😃
    design:
      columns: '1'

  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2

  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1

  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 0
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

  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
