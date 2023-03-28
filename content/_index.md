---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # - block: hero
  #   content:
  #     title: Jiefeng Ma's Homepage
  #     image:
  #       filename: ai.png
  #     # cta:
  #     #   label: '**Get Started**'
  #     #   url: https://wowchemy.com/templates/
  #     # cta_alt:
  #     #   label: Ask a question
  #     #   url: https://discord.gg/z8wNYzb
  #     # cta_note:
  #     #   label: >-
  #     #     <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
  #     text: |-
  #       **I'm currently a PhD candidate of USTC.**

  #       **My research interest focuses on Document Intelligence and Multimodal Learning.**

  #       Including:

  #       - Document key information extraction
  #       - Document structure analysing
  #       - Text-vision LLM
  #       - General AIGC

      #   <!--Custom spacing-->
      #   <div class="mb-3"></div>
      #   <!--GitHub Button JS-->
      #   <script async defer src="https://buttons.github.io/buttons.js"></script>
    # design:
    #   background:
    #     gradient_end: '#1976d2'
    #     gradient_start: '#004ba0'
    #     text_color_light: true
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
        - name: Linux
          description: 70%
          icon: linux
          icon_pack: fab
        - name: Markdown
          description: 70%
          icon: markdown
          icon_pack: fab
        - name: C++
          description: 70%
          icon: c
          icon_pack: fas
        - name: Photography
          description: 50%
          icon: camera-retro
          icon_pack: fas
        - name: Shell
          description: 50%
          icon: terminal
          icon_pack: fas

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
        - certificate_url: https://stuhome.ustc.edu.cn/2019/0528/c2299a381732/page.htm
          date_end: '2019-07-01'
          date_start: '2017-07-01'
          description: 'Silver Award **(Top 10%)** / Gold Award **(Top 1%)** / Silver Award **(Top 10%)**'
          organization: USTC
          organization_url: http://en.ustc.edu.cn/
          title: Excellent Student Scholarship
          url: 'https://stuhome.ustc.edu.cn/2019/0528/c2299a381732/page.htm'
        - certificate_url: http://news.ustc.edu.cn/info/1032/22010.htm
          date_end: '2018-10-30'
          date_start: '2018-07-01'
          description: 'Served as the **team leader**, in charge of mechanical structure design and code implemention on STM-32.'
          organization: USTC
          organization_url: http://en.ustc.edu.cn/
          title: 'First Prize in RoboGame Competition'
          url: 'http://news.ustc.edu.cn/info/1032/22010.htm'
        - certificate_url: https://stuhome.ustc.edu.cn/2020/0705/c2299a435809/pagem.htm
          date_end: ''
          date_start: '2020-07-05'
          description: 'Selected as **outstanding graduate** of the school in 2020.'
          organization: USTC
          organization_url: http://en.ustc.edu.cn/
          title: 'Outstanding Graduate'
          url: 'https://stuhome.ustc.edu.cn/2020/0705/c2299a435809/pagem.htm'
        - certificate_url: https://sist.ustc.edu.cn/2018/0531/c5101a263342/page.htm
          date_end: '2019-05-01'
          date_start: '2018-05-01'
          description: 'Served as the **vice president** of School of Information Science and Technology Student Union, in charge of the practice and volunteer team.'
          organization: USTC
          organization_url: https://en.sist.ustc.edu.cn/main.htm
          title: 'Vice President of the School Student Union'
          url: 'http://news.ustc.edu.cn/info/1032/22010.htm'
        - certificate_url: http://stuhome.ustc.edu.cn/2018/0506/c2314a259049/pagem.htm
          date_end: '2018-05-01'
          date_start: '2017-05-01'
          description: 'Served as the **president** of the USTC School of Information Science and Technology Youth Volunteer Association and Youth League Committee Office.'
          # , planned and organized activities such as "4:30 Classroom" and Science and Technology Exhibition, serving over two thousand students and citizens
          organization: USTC
          organization_url: https://en.sist.ustc.edu.cn/main.htm
          title: 'President of the School Youth Volunteer Association and Youth League Committee Office'
          url: 'https://en.sist.ustc.edu.cn/main.htm'
        - certificate_url: https://www.heywhale.com/home/competition/5f703ac023f41e002c3ed5e4/leaderboard
          date_end: '2020-10-01'
          date_start: '2020-09-01'
          description: '**First place winner** of the Education Handwritten Formula Recognition Competition in the Smart Education Subject Competition of the 5th China Innovation Challenge. (1/250)'
          organization: Heywhale
          organization_url: https://www.heywhale.com/home/
          title: 'First Place Winner'
          url: 'https://www.heywhale.com/home/competition/5f703ac023f41e002c3ed5e4/leaderboard'
    design:
      columns: '2'

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
        - title: Research Intern - Multimodal Content Understanding
          company: Super-Brain group, iFLYTEK Research
          company_url: 'https://global.iflytek.com/iflytek-open-platform/'
          company_logo: iflytek
          date_start: '2022-03-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * PDF parser system
              * Document reconstruction
              * Mathematical reasoning

              Collaborators and Friends: [Jianshu Zhang (张建树)](http://home.ustc.edu.cn/~xysszjs/), [Zhenrong Zhang (张镇荣)](https://www.researchgate.net/scientific-contributions/Zhenrong-Zhang-2202217766), [Pengfei Hu (胡鹏飞)]
        
        - title: Research Intern - Document AI
          company: YouTu Lab, Tencent
          company_url: 'https://open.youtu.qq.com/#/open'
          company_logo: tencent-youtu
          date_start: '2020-10-01'
          date_end: '2021-10-01'
          description: |2-
              Responsibilities include:

              * Document layout pretrain
              * Document key information extraction
              * Few-shot & zero-shot learning

              Collaborators and Friends: [Haoyu Cao (曹浩宇)](https://scholar.google.com/citations?user=LV8ejn8AAAAJ&hl=zh-CN), [Zhongzhong Li (李中中)](http://home.ustc.edu.cn/~lizhogn/), [Sheng Kang (康昇)](https://techkang.github.io/), [Wenwen Yu (余文文)](https://www.yuwenwen.site/)
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
      title: Recent Publications
      filters:
        folders:
          - publication
        # featured_only: true
    design:
      columns: '2'
      view: card

  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact

  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        If you have any problems on my projects, please feel free to contact me.
      # Contact (add or remove contact options as necessary)
      # email: jfma@mail.ustc.edu.cn
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: Yanzi He Road
        city: Hefei
        region: Anhui
        postcode: '231283'
        country: China
        country_code: Cn
      directions: Room 202, 2nd Floor, Xinzhi Building, High-tech Campus, University of Science and Technology of China.
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: envelope
          icon_pack: fas
          name: Mail Me
          link: mailto:jfma@mail.ustc.edu.cn
        - icon: github
          icon_pack: fab
          name: Star Me
          link: https://github.com/jfma-USTC
        - icon: weixin
          icon_pack: fab
          name: Chat Me
          link: uploads/weixin.jpg
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
