---
# Leave the homepage title empty to use the site title
title: 'Christian Dale G. Santos'
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
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: balanced # Options: compact (long names), balanced (default), display (short names)

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 Capstone Research'
      subtitle: ''
      image: '/static/capstone.png'
      text: |-
        The Furmates prototype is an early iteration of a centralized web-based platform for managing dog adoption and shelters that aims to improve shelter operations and adopters' experiences in Metro Manila. Essential functions including pet listing administration, adoption application tracking, messaging, and donation facilitation are all included in this prototype. Furmates is a digital technology that streamlines manual shelter workflows by replacing them with automated systems.

        Please reach out to collaborate
    design:
      columns: '1'
  -
---
