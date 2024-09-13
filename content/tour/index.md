---
title: Tour
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
            filename: people.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Omnidirectional Depth Estimation
        content: ''
        align: right
        background:
          image:
            filename: slide_depth.png
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Learn More
          url: ../depth/
      - title: Integrated Sensing and Computing
        content: ''
        align: right
        background:
          image:
            filename: slide_sensor.png
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Learn More
          url: ../integrated/
      - title: Occupancy Network
        content: 'Omnidirectional Depth-Aided Occupancy Prediction based on Cylindrical Voxel for Autonomous Driving'
        align: right
        background:
          image:
            filename: occ_slide.png
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Learn More
          url: ../occ/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---
