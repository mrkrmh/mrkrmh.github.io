---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: "Research Profile"
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I am a FAPESP postdoctoral researcher at **Universidade do Vale do Paraíba (UNIVAP)** investigating the chemical composition of galaxies. My research focuses on **Active Galactic Nuclei (AGNs)**, specifically Seyfert galaxies, and the interplay between gas inflow, outflow, and consumption.
        
        Using the **Cloudy** spectral synthesis code and photoionization models, I develop metallicity calibrations to accurately determine the chemical abundances in ionized gas. I am particularly interested in how these processes impact galaxy evolution across cosmic time.

    design:
      columns: '1'

  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
