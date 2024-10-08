---
title: Depth
date: 2022-10-24

type: landing

sections:
  - block: hero
    content:
      title: |
        Depth Estimation
      image:
        filename: depth.png
      text: |
        <br>
        
        A Lightweight Omnidirectional Depth Estimation System based on Spherical Sweeping for Autonomous Driving
  
  #- block: collection
  #  content:
  #    title: Latest News
  #    subtitle:
  #    text:
  #    count: 5
  #    filters:
  #      author: ''
  #      category: ''
  #      exclude_featured: false
  #      publication_type: ''
  #      tag: ''
  #    offset: 0
  #    order: desc
  #    page_type: post
  #  design:
  #    view: card
  #    columns: '1'
  
  #- block: markdown
  #  content:
  #    title: Abstract
  #    subtitle: ''
  #    text: Accurate 3D perception is essential for autonomous driving. Traditional methods often struggle with geometric ambiguity and slow convergence due to a lack of geometric prior. To address this challenge, we use omnidirectional depth estimation, which is generated by our lab's XXXNET, to introduce geometric prior. Based on the depth information, We propose a cylindrical voxel-based Sketch-Coloring framework. Additionally, our approach introduces a cylindrical voxel representation based on polar coordinate, better aligning with the radial nature of panoramic camera views. This representation adjusts voxel density according to distance, boosting the performance of close proximity. We also build a virtual scene dataset with six fisheye cameras, addressing the lack of fisheye camera dataset in autonomous driving tasks. Experimental results demonstrate that our Sketch-Coloring network significantly enhances 3D perception performance, especially in nearby regions, which makes our method a promising solution for autonomous driving perception.
  - block: markdown
    content:
      title: Experiment Setup
      subtitle: 'We build a system on a remote-controlled car to simulate autonomous driving scenarios.'
      text: <p> <img  src="car.png" align="center" width="1250" /> </p>
  - block: markdown
    content:
      title: Experimental Result
      subtitle: ''
      text: <center><big><b>Qualitative Result</b></big></center> <br> <p> <img  src="depth_display.jpg" align="center" width="1250" /> <br>We have achieved good result in real-world scenarios, which can effectively reconstruct the surrounding environment of the vehicle. </p><br> <center><big><b>More Demo Video</b></big></center> <br> <center>A DEMO of driving on the road</center> <br> <video src="ground2.mp4" autoplay="autoplay" loop="loop" controls="controls"></video> <br> <center>A DEMO of driving in the underground parking lot</center> <br> <video src="underground1.mp4" autoplay="autoplay" loop="loop" controls="controls"></video>
  #add some unique images
    #design:
    #  columns: '1'
    #  background:
    #    image: 
    #      filename: coders.jpg
    #      filters:
    #        brightness: 1
    #      parallax: false
    #      position: center
    #      size: cover
    #      text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  #- block: collection
  #  content:
  #    title: Latest Preprints
  #    text: ""
  #    count: 5
  #    filters:
  #      folders:
  #        - publication
  #      publication_type: 'article'
  #  design:
  #    view: citation
  #    columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
