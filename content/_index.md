---
title: ''
summary: ''
date: 2024-01-01
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/CV_Baran.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '🔬 Research'
      subtitle: ''
      text: |-
        I am an Assistant Professor in the [Department of Information Systems Engineering](https://www.sakarya.edu.tr/)
        at Sakarya University. Previously, I was a Postdoc Researcher at the
        [University of Iowa Hydroinformatics Lab](https://hydroinformatics.uiowa.edu/) (2023–2025).
        My work sits at the intersection of **Hydroinformatics**, **IoT-based environmental monitoring**,
        and **web technologies for science communication**.

        I develop open-source tools and platforms that make hydrological data more accessible
        for education and decision-making. I also work on cloud computing architectures and
        distance education systems.

        **Full CV with contact details available** — [view protected page](/private/) *(access code required — [request one](mailto:baran@kaynak.me))*
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: projects
    content:
      title: Research Projects
      filters:
        folders:
          - projects
    design:
      view: card
---
