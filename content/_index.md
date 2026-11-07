---
title: ''
summary: ''
type: landing

sections:
  - block: resume-biography-3
    id: about
    content:
      # Author profile is defined in data/authors/me.yaml
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: collection
    id: research
    content:
      title: Research
      filters:
        folders:
          - research
    design:
      view: card
      columns: 2

  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publications
    design:
      view: citation
      columns: 2

  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - talks
    design:
      view: citation
      columns: 2

  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      view: list
      columns: 2

  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        **Sandra Auderset**<br>
        Department of Linguistics, University of Bern<br>
        Office B163, Länggassstrasse 49, 3012 Bern, Switzerland<br>
        ✉️ [sandra.auderset@unibe.ch](mailto:sandra.auderset@unibe.ch)
    design:
      columns: 2
---
