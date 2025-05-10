---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # - block: hero
  #   content:
  #     title: |
  #       <div style="font-size: 32px; font-weight: bold;">Special Interest Group on Mining and learning from datA  </div><div style="font-size: 18px; font-weight: bold; line-height: 2.5;">SIGMA@OUC</div>
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       <br>
  #       XXXX。。。。。
  - block: slider
    content:
      items:
        - title: 欢迎来到SIGMA实验室
          subtitle: 我们致力于挖掘数据的价值
          image:
            filename: welcome.jpg
          content: |
            探索我们的研究领域，加入我们！
          cta:
            label: 了解更多 →
            url: ./research/

        - title: 招募优秀学生
          subtitle: 本科生 / 研究生 / 博士后
          image:
            filename: icon.png
          content: |
            如果你对数据挖掘、图学习感兴趣，欢迎联系我们！
          cta:
            label: 加入我们 →
            # url: ./join/
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: list
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
