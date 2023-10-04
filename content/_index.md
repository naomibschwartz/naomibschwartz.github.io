---
# Leave the homepage title empty to use the site title
title: Schwartz Geospatial Ecology Lab
date: 2022-10-24
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
        align: left
        background:
          image:
            filename: TallGrass.png
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Learn More about Our Research
        content: 
        align: right
        background:
          image:
            filename: WilliamsLake_droneshot.png
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
