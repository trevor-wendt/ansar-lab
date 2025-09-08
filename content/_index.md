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
        Cerebrovascular Biology - Clinical Translational - Neurovascular Disease
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The Ansar Lab is committed to advancing our understanding of the cerebrovasculature, integrating multifaceted molecular, cellular, and systems-level approaches. By fostering collaborations with international clinical and preclinical partners, we aim to bridge fundamental mechanistic discoveries with translational applications, ultimately driving innovation in diagnostics and therapeutics for cerebrovascular and neurological disorders.
  
- block: slider
  content:
    title: Research Projects
    slides:
      - title: Preclinical High-Throughput
        content: 'Scalable in-vitro assays, imaging, and analytics to accelerate discovery and screening'
        align: left
        link:
          text: Learn more →
          url: "/tour#preclinical-high-throughput"
        background:
          image:
            filename: project-preclinical-high-throughput.jpg
            filters:
              brightness: 0.75
          parallax: false
          position: center
          size: cover
      - title: Preclinical In Vivo
        content: 'Robust in-vivo models of cerebrovascular disease compatible for in-depth mechanistic and functional queries'
        align: left
        link:
          text: Learn more →
          url: "/tour#preclinical-in-vivo"
        background:
          image:
            filename: project-preclinical-in-vivo.jpg
            filters:
              brightness: 0.75
          parallax: false
          position: center
          size: cover
      - title: Clinical Translation
        content: 'Bridging preclinical insights into translational frameworks, biomarkers, prediction models, and trial-ready endpoints'
        align: left
        link:
          text: Learn more →
          url: "/tour#clinical-translation"
        background:
          image:
            filename: project-clinical-translation.jpg
            filters:
              brightness: 0.75
          parallax: false
          position: center
          size: cover
      - title: Clinical Studies
        content: 'Clinical studies and real-world evidence to validate safety, effectiveness, and equity of interventions as well as identify future biomarkers for therapeutic intervention and monitoring'
        align: left
        link:
          text: Learn more →
          url: "/tour#clinical"
        background:
          image:
            filename: project-clinical.jpg
            filters:
              brightness: 0.75
          parallax: false
          position: center
          size: cover
  design:
    height: "420px"        # keeps it compact (try 360–480px to taste)
    spacing:
      padding: ["16px","0","24px","0"]
    css_class: slider-compact


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
