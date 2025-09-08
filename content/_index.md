---
title: ""
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        ANSAR LAB
        Cerebrovascular Biology • Clinical Translational • Neurovascular Disease
      image:
        filename: welcome.jpg
      text: |
        <br>
        The Ansar Lab is committed to advancing our understanding of the cerebrovasculature, integrating multifaceted molecular, cellular, and systems-level approaches. By fostering collaborations with international clinical and preclinical partners, we aim to bridge fundamental mechanistic discoveries with translational applications, ultimately driving innovation in diagnostics and therapeutics for cerebrovascular and neurological disorders.
    design:
      spacing:
        padding: ["24px","0","24px","0"]

  - block: slider
    content:
      title: Research Projects
      slides:
        - title: "Preclinical High-Throughput"
          content: "Scalable in-vitro assays, imaging, and analytics to accelerate discovery and screening"
          align: left
          image:
            filename: project-preclinical-high-throughput.jpg
            focal_point: Center
            alt_text: High-throughput BBB screening

        - title: "Preclinical In-Vivo"
          content: "In-vivo models of cerebrovascular disease"
          align: left
          image:
            filename: project-preclinical-in-vivo.jpg
            focal_point: Center
            alt_text: Rodent Models

        - title: "Clinical Translation"
          content: "Biomarkers, exposure modeling, and patient-linked outcomes."
          align: left
          image:
            filename: project-clinical-translation.jpg
            focal_point: Center
            alt_text: Clinical translation workflow

        - title: "Clinical Studies"
          content: "Clinical studies and real-world evidence to validate interventions and identify biomarkers."
          align: left
          image:
            filename: project-clinical.jpg
            focal_point: Center
            alt_text: Clinical studies
    design:
      height: "420px"
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
        publication_type: "article"
    design:
      view: citation
      columns: "1"

  - block: markdown
    content:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: "1"
---
