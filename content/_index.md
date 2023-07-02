---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: handsomecat.png
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Our robot
        content: this is our robot
        align: left
        background:
          image:
            filename: robot_pic.PNG
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Our robot movie
        content: this is our robot movie
        align: left
        background:
          image:
            filename: robot_mv_comp.MP4
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 'DoReMi: Grounding Language Model by Detecting and Recovering from Plan-Execution Misalignment'
        align: right
        background:
          image:
            filename: DoReMi_pic.png
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Arxiv
          url: 'https://arxiv.org/'
      - title: Decentralized Motor Skill Learning for Complex Robotic Systems
        align: right
        background:
          image:
            filename: DEMOS_pic.png
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Arxiv
          url: 'https://arxiv.org/'
      - title: 'Asking Before Action: Gather Information in Embodied Decision Making with Language Models'
        align: right
        background:
          image:
            filename: ABA_pic.png
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Arxiv
          url: 'https://arxiv.org/abs/2305.15695'
      - title: AMP
        align: right
        background:
          image:
            filename: handsomecat.png
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Arxiv
          url: 'https://arxiv.org/'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
  
  - block: hero
    content:
      title: |
        Intelligent Systems and Robotics Lab
      image:
        filename: combined_logo.png
      text: |
        <br>
        
        'The Intelligent Systems and Robotics Lab (ISRLab) is founded by [Prof. Jianyu Chen](http://people.iiis.tsinghua.edu.cn/~jychen/). It is affiliated with the Institute for [Interdisciplinary Information Sciences (IIIS)](https://iiis.tsinghua.edu.cn/) at Tsinghua University, and the [Shanghai Qizhi Institute](https://sqz.ac.cn). Our goal is to build advanced robotic systems with high performance and high intelligence. We work in the cross fields of robotics, reinforcement learning, and large language models.'
---
