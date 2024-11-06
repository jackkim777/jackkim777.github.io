---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections: 
  - block: features
    content:
      title: <span style="font-size:70%">신서현의 홈페이지에 오신 것을 환영합니다.</span>
      text: <br><span style="font-size:125%">저는 전북대학교 컴퓨터인공지능학부에 재학 중이며, 인공지능(AI) 분야, 특히 머신러닝과 컴퓨터 비전에 많은 관심을 가지고 있습니다. 앞으로 인공지능 분야에서 깊이 있는 연구를 이어가며 성과를 이루는 개발자가 되고 싶습니다.</span> <br><br>
        {{% cta cta_link="./about/" cta_text="About me →" %}}


  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:60%">인간의 지능을 모방해 문제 해결, 학습, 패턴 인식 등의 작업을 자동으로 수행하는 기술</span>
        align: center
        background:
          image:
            filename: image1_ai.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'

      - title: <span style="font-size:70%">Computer Vision</span>
        content: <span style="font-size:60%">이미지를 분석하고 이해하여 객체 인식, 장면 해석, 동작 추적 등 시각적 데이터를 처리하는 AI 기술 분야</span>
        align: left
        background:
          image:
            filename: image2_cv.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'

      - title: <span style="font-size:70%">Machine Learning</span>
        content: <span style="font-size:70%">데이터로부터 패턴을 학습하고 예측을 수행하도록 컴퓨터를 훈련시키는 AI 기술</span>
        align: right
        background:
          image:
            filename: image3_ml.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">창의적인 아이디어를 기술적으로 구현하고, 소프트웨어와 시스템을 설계, 구축, 유지보수하는 과정</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.5
          position: left
          color: '#333'

      - title: <span style="font-size:70%">Contact</span>
        content: <span style="font-size:70%">How to contact me...</span>
        align: center
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
            icon: graduation-cap
            icon_pack: fas
            text: contact me
            url: ../contact/

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '400px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: portfolio
    content:
      title: Projects
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: ALL
          tag: '*'
          type: project
        - name: 쿠키런 변형 게임
          tag: CR
        - name: 홈페이지 만들기
          tag: HMP
        - name: 맛집 탐색 서비스
          tag: MJ  
    design:
      columns: '1'
      view: custom_card
      flip_alt_rows: false
      spacing: { padding: [30, 0, 30, 0] }

  - block: collection
    content:
      title: notice
      subtitle:
      text:
      count: 3
      filters:
        folders:
          - notice
          - gallery
      offset: 0
      order: desc
      #page_type: publication
    design:
      view: community/custom_compact
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: collection
    content:
      title: Upcoming Events
      subtitle:
      text:
      count: 3
      filters:
        folders:
          - events
      offset: 0
      order: desc
      page_type: events
    design:
      view: masonry
      columns: '2'
    advanced:
      css_style: "text-align: center;"
---