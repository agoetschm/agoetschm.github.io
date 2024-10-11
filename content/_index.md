---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    # design:
    #   css_class: dark
    #   background:
    #     color: black
    #     image:
    #       # Add your image background to `assets/media/`.
    #       filename: stacked-peaks.svg
    #       filters:
    #         brightness: .45
    #       size: cover
    #       position: center
    #       parallax: false
    design:
      background:
        # color: WhiteSmoke
        # color: OldLace
        # color: SeaShell
        color: Linen
    
  - block: collection
    id: publications
    content:
      title: 'Research'
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: resume-experience
    id: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  # - block: markdown
  #   id: dev
  #   content:
  #     title: 'Development'
  #     subtitle: ''
  #     text: |-
  #       #### [Inria](https://team.inria.fr/pesto/)

  #       Contribution to the [Belenios](https://belenios.org) voting system

  #       _E-voting_ · _OCaml_
        
  #       ---

  #       #### [Lunatech](https://lunatech.com/)

  #       Development and operation of a vehicle data ingestion pipeline for Audi

  #       _Akka Streams_ · _Scala_ · _DevOps_ · _Kubernetes_ · _Grafana_
        
  #       ---

  #       #### [Nevis](https://www.nevis.net)

  #       Kubernetes operator managing components of the Nevis Security Suite

  #       _Kubernetes_ · _Go_
        
  #       ---

  #       #### [Open Systems](https://www.open-systems.com/)

  #       Managaging configurations and monitoring of over 4000 hosts around the world

  #       _Observability_ · _Perl_ · _Go_

  #   design:
  #     columns: '1'
---
