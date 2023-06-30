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
      - title: Lunch & Learn ☕️
        content: We realllly eat a lot.
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Research works 📄
        content: our new research 
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
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
        filename: handsomecat.png
      text: |
        <br>
        
        'The **Intelligent Systems and Robotics** (ISR) Lab is the world number one robotics lab leading by great Prof. Chen. I am an assistant professor in Institute for Interdisciplinary Information Sciences (IIIS) at Tsinghua University. Prior to that, I was working with Prof. Masayoshi Tomizuka at the University of California, Berkeley and received my Ph.D. degree in 2020. I received my Bachelor degree from Tsinghua University in 2015. I am working at an intersection of machine learning, robotics and control to build intelligent systems which can efficiently learn safe and reliable sensori-motor control policies. Applications of my work mainly focus on robotic systems such as autonomous driving and industrial robots. My research interests include reinforcement learning, control, deep learning, autonomous driving, and robotics.'
---
