---
title: Interests
type: landing

sections:
  - block: features
    content:
      title: My Interests
      subtitle: I am interested in...
    # text: 
      items:
        - name: Autonomous Car
          # description: 90%
          icon: fa fa-car
          icon_pack: fas
        - name: SLAM
          # description: 100%
          icon: fa-location-arrow
          icon_pack: fas
        - name: Computer Vision
          # description: 10%
          icon: eye
          icon_pack: fas
        - name: Deep Learning
          # description: 10%
          icon: magnifying-glass-chart
          icon_pack: fas
        - name: Sensor Fusion
          # description: 10%
          icon: fa-mixcloud
          icon_pack: fas
        - name: Robotics
          # description: 10%
          icon: robot
          icon_pack: fas

  - block: slider
    content:
      slides:
      - title: 앞으로의 계획 및 목표
        content: My goal is...
        align: center
        background:
          image:
            filename: goal.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: 심화 학습 및 프로젝트 진행
        content: pyTorch와 같은 프레임워크를 공부하여 기술 스택을 강화하고 관련 프로젝트를 진행할 예정입니다.
        align: left
        background:
          image:
            filename: study.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 인공지능 연구자이자 개발자로
        content: 연구를 통해 학문적 성취를 이루고, 이를 바탕으로 ai 연구 및 개발자로 성장하고자 합니다.
        align: right
        background:
          image:
            filename: mygoal.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---