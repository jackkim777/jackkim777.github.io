---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections: 
  - block: features
    content:
      title: "<span style=\"font-size:70%\">김윤성의 홈페이지에 오신 것을 환영합니다.</span>"
      text: >
        <br><span style="font-size:125%">저는 전북대학교 전자공학부에 재학 중이며, 자율주행과 SLAM (Simultaneous Localization and Mapping) 기술에 큰 관심을 가지고 있습니다. 특히 2D SLAM, 3D SLAM, 센서 융합(Sensor Fusion), 그리고 Visual SLAM 분야에 열정을 가지고 있습니다.</span> <br><br>
        {{% cta cta_link="./about/" cta_text="About me →" %}}


  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">Autonomous Car</span>
        content: <span style="font-size:60%">자율 주행 차량은 주변 환경을 인식하고, 경로를 계획하며 스스로 운행하는 첨단 기술로 다양한 센서를 활용</span>
        align: center
        background:
          image:
            filename: image1_ai.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'

      - title: <span style="font-size:70%">SLAM</span>
        content: <span style="font-size:60%">동시에 로봇의 위치를 추정하고 환경을 매핑하는 기술로, 자율 주행 및 로봇 내비게이션에 핵심적인 역할을 수행</span>
        align: left
        background:
          image:
            filename: image3_ml.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'

      - title: <span style="font-size:70%">Deep Learning</span>
        content: <span style="font-size:70%">대량의 데이터를 활용하여 복잡한 패턴을 학습하고 예측을 수행하는 AI 기술, 인공신경망을 기반으로 한다</span>
        align: right
        background:
          image:
            filename: image2_cv.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

      - title: <span style="font-size:70%">Sensor Fusion</span>
        content: <span style="font-size:70%">다양한 센서의 데이터를 통합하여 정확하고 신뢰성 높은 정보를 제공, 자율 주행 및 로봇 시스템에서 중요한 역할을 수행</span>
        align: center
        background:
          image:
            filename: image4_tt.jpg
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
        - name: 창의적 공학 설계 입문
          tag: IOT
        - name: 2023 KATRI 대회
          tag: 2023katri
        - name: 2024 KATRI 대회
          tag: '*'
        - name: 학부연구생
          tag: MJ  
        - name: 캠스톤 디자인
          tag: SF
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