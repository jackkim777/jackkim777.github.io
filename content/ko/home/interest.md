---
# A section created with the Slider widget.
widget: slider

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

content:
  slides:
    - title: AI
      content: 인간의 지능을 모방해 문제 해결, 학습, 패턴 인식 등의 작업을 자동으로 수행하는 기술
      align: center
      background:
        image:
          filename: image1_ai.jpg
          filters:
            brightness: 0.7
        position: right
        color: '#666'
    - title: Computer Vision
      content: 이미지를 분석하고 이해하여 객체 인식, 장면 해석, 동작 추적 등 시각적 데이터를 처리하는 AI 기술 분야
      align: left
      background:
        image:
          filename: image2_cv.jpg
          filters:
            brightness: 0.7
        position: center
        color: '#555'
    - title: Machine Learning
      content: 데이터로부터 패턴을 학습하고 예측을 수행하도록 컴퓨터를 훈련시키는 AI 기술
      align: right
      background:
        image:
          filename: image3_ml.jpg
          filters:
            brightness: 0.5
        position: center
        color: '#333'
    - title: Development
      content: 창의적인 아이디어를 기술적으로 구현하고, 소프트웨어와 시스템을 설계, 구축, 유지보수하는 과정
      align: center
      background:
        image:
          filename: image3_ml.jpg
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