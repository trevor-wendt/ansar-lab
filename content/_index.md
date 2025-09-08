---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        ANSAR LAB
        Cerebrovascular Biology - Clinical Translational - Neurovascular Disease - Nanomedicine - Environmental Health
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The Ansar Lab is committed to advancing our understanding of the cerebrovasculature, with a central focus on the Blood-Brain-Barrier (BBB) as a critical regulator of brain health and disease. Our research integrates molecular, cellular, and systems-level approaches to dissect mechanisms of cerebrovascular injury and repair, spanning models of ischemic stroke, neurodegeneration, and environmental exposures. By fostering collaborations with international clinical and preclinical partners, we aim to bridge fundamental mechanistic discoveries with translational applications, ultimately driving innovation in diagnostics and therapeutics for cerebrovascular and neurological disorders.
  
  - block: collection
    content:
      title: Research Projects
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
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Publications & Preprints
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
