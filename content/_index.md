---
# Leave the homepage title empty to use the site title
title: Schwartz Geospatial Ecology Lab
date: 2023-10-11
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Welcome to the <br> Schwartz Geospatial Ecology Lab!
        align: center
        background:
          image:
            filename: Forest.png
            filters:
              brightness: 0.7
          position: right
          color: '#333'
      - title: Who We Are
        content: Climate and land-use change are altering the frequency and intensity of disturbance and climate extremes. Our Lab uses remote sensing and GIS, combined with field research methods, to address questions about the causes and consequences of disturbance and extreme events in forest landscapes.
        align: center
        background:
          image:
            filename: TallGrass.png
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Our Research
        content: Our lab addresses questions about the causes and consequences of disturbance and extreme events in forest landscapes, mostly in tropical regions. Climate and land-use change are already altering the frequency and intensity of disturbance and climate extremes. To address these themes, we use a variety of tools including remote sensing and GIS, forest censuses, plant functional trait measurements, and socio-economic surveys.
        align: center
        background:
          image:
            filename: WilliamsLake_droneshot.png
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: seedling
          icon_pack: fas
          text: Check Out Our Projects
          url: ../research/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
      
---
