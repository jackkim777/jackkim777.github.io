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
        align: center
        background:
          image:
            filename: image1_ai.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'

      - title: <span style="font-size:70%">SLAM</span>
        align: left
        background:
          image:
            filename: image3_ml.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'

      - title: <span style="font-size:70%">Deep Learning</span>
        align: right
        background:
          image:
            filename: image2_cv.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

      - title: <span style="font-size:70%">Sensor Fusion</span>
        align: center
        background:
          image:
            filename: image4_tt.jpg
            filters:
              brightness: 0.5
          position: left
          color: '#333'


      - title: <span style="font-size:70%">Contact</span>
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
          tag: 2024katri
        - name: 학부연구생
          tag: MJ  
        - name: 캠스톤 디자인
          tag: HMP
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
---