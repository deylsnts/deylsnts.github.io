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
  - block: hero
    content:
      title: 'College Life Reflections'
      subtitle: ''
      text: |-
      
        College life at De La Salle–College of Saint Benilde has been a journey of growth and discovery. Balancing classes, projects, and campus life can be challenging, but it teaches resilience and time management. Meeting diverse classmates, joining activities, and working on real projects has helped me learn, connect, and grow. Beyond academics, college is about finding passions, building friendships, and preparing for life beyond the classroom.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 1
  
---
