---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        NJU-EE Autonomous Driving Research Group
      image:
        filename: lab.jpg
      text: |
        <br>
        
        The **NJU-EE Autonomous Driving Research Group** focus on developing vision-based perception algorithms for autonomous driving.
  
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
  
  - block: markdown
    content:
      title: Application Area
      subtitle: ''
      text: <p> <img  src="auto_car.png" align="right" width="500" /> <br> Accurate 3D perception is essential for autonomous driving. Addressing the environmental perception requirements of autonomous driving, we have conducted research into omnidirectional depth estimation algorithm. Building upon this foundation, we have further explored integrated sensing and computing algorithm deployed on hardware, as well as occupancy network aided by depth information.</p>
    design:
      columns: '1'
      #background:
      #  image: 
      #    filename: coders.jpg
      #    filters:
      #      brightness: 1
      #    parallax: false
      #    position: center
      #    size: cover
      #    text_color_light: true
      #spacing:
      #  padding: ['20px', '0', '20px', '0']
      #css_class: fullscreen
  - block: markdown
    content:
      title: Research Direction
      subtitle: ''
      text: <p><center><big><b>Depth Estimation </center></big></b></p> <br> We have studied depth estimation from multi-camera systems to obtain structural information of the surrounding environment for autonomous driving systems. Here is a demo video. More details are available in <a href="https://nju-ee.github.io/Autonomous_Driving_Research_Group.page/depth/" title="Depth Estimation">this page</a> <br><br> <video src="ground1.mp4" autoplay="autoplay" loop="loop" controls="controls"></video>
  - block: markdown
    content:
      title: 
      subtitle: ''
      text: <p><center><big><b> Integrated Sensing and Computing </center></big></b></p> <br> We propose an omnidirectional depth estimation system based on near-sensor computing architecture. The proposed work achieves load balancing by task partitioning, while reducing transmission bandwidth through the feature projection and learnable codec. More details are available in <a href="https://nju-ee.github.io/Autonomous_Driving_Research_Group.page/integrated/" title="Integrated Sensing and Computing">this page</a> <br><br> <p><img  src="Fig2.drawio.png" align="center" width="1250"  /> </p>
  - block: markdown
    content:
      title: 
      subtitle: ''
      text: <p><center><big><b> Occupancy Network </center></big></b></p> <br>  Based on the depth information provided by our lab's Depth Estimation Network, we propose a Sketch-Coloring framework based on cylindrical voxel.  Here is a demo video. Experimental results demonstrate that our Sketch-Coloring network significantly enhances 3D perception performance, especially in nearby regions, which makes our method a promising solution for autonomous driving perception. More details are available in <a href="https://nju-ee.github.io/Autonomous_Driving_Research_Group.page/occ/" title="Occupancy Network">this page</a> <br><br> <video src="occ_output_subtitle.mp4" loop="loop" controls="controls"></video>
  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
