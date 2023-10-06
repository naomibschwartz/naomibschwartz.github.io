---
title: Research
date: 2022-10-24

type: landing

sections:
  - block: markdown
    id: intro
    content:
      title: Our Research
      text: Our lab’s research addresses questions about the causes and consequences of disturbance and extreme events in forest landscapes, mostly in tropical regions. Climate and land-use change are already altering the frequency and intensity of disturbance and climate extremes. Can we predict which forests will be most vulnerable to these events? What are the processes that underlie spatial heterogeneity in forest responses to disturbance and climate extremes? How do these events shape forest landscapes? To address these themes, we use a variety of tools including remote sensing and GIS, forest censuses, plant functional trait measurements, and socio-economic surveys.
    design:
      columns: '2'
      background:
        text_color_light: true
        image:
          filename: green-vegetation.jpeg
          filters: 
            brightness: 0.3
          size: cover
          position: center
          parallax: true
  - block: portfolio
    id: projects
    content:
      title: Active Projects
      subtitle: My subtitle
      filters:
        folders:
          - projects
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: All
          tag: '*'
    design:
      columns: '1'
      view: showcase
      flip_alt_rows: false
---

