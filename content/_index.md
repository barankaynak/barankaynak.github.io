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
        at Sakarya University (Faculty of Computer and Information Sciences). Previously, I was a
        Postdoc Researcher at the [University of Iowa Hydroinformatics Lab](https://hydroinformatics.uiowa.edu/) (2023–2025).

        My research spans **Hydroinformatics**, **IoT-based environmental monitoring**, **cloud computing**,
        and **blockchain technologies**. I build open-source tools and platforms that make hydrological
        and environmental data accessible for education and decision-making.

        Before academia, I spent a decade as a software developer and system administrator at Sakarya University,
        designing and operating large-scale university information systems, Kubernetes infrastructure,
        and the national distance education platform [UZEP](https://uzep.org).

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
