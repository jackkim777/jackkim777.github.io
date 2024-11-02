---
# A section created with the Slider widget.
widget: slider

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

content:
  slides:
    - title: Autonomous Vehicle
      content: 자율적으로 주행하며 환경을 인식하고 의사 결정을 내리는 차량 기술
      align: center
      background:
        image:
          filename: 자율주행.jpg
          filters:
            brightness: 0.7
        position: right
        color: '#666'
    - title: SLAM
      content: 동시에 위치 추정과 지도 작성을 수행하는 기술로, 로봇과 자율주행에서 중요한 역할
      align: left
      background:
        image:
          filename: SLAM.jpg
          filters:
            brightness: 0.7
        position: center
        color: '#555'
    - title: Deep Learning
      content: 인공신경망을 활용해 대량의 데이터를 학습하고 예측하는 고도화된 AI 기술
      align: right
      background:
        image:
          filename: 딥러닝.jpg
          filters:
            brightness: 0.5
        position: center
        color: '#333'
    - title: Sensor Fusion
      content: 여러 센서 데이터를 결합해 더 정확한 정보를 얻는 기술, 자율주행과 로봇 공학에서 중요함
      align: center
      background:
        image:
          filename: 센서퓨전.jpg
          filters:
            brightness: 0.5
        position: left
        color: '#333'

      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/

design:
  slide_height: ''
  is_fullscreen: true
  loop: true
  interval: 3000
  spacing: {padding: [20, 0, 20, 0]}
---