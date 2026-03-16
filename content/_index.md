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
      username: me
      text: |-
        I build practical analytics tools for operations teams, with a focus on supply chain visibility,
        procurement planning, and dashboards that help teams act faster.
      button:
        text: View Resume
        url: /experience/
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: About
      subtitle: ''
      text: |-
        I am a San Jose-based data analyst with experience in business analytics, supply chain reporting,
        and operational decision support. My recent work has centered on building SQL-based reporting,
        automating planning workflows, and creating Power BI, Tableau, and Sigma dashboards for procurement
        and operations teams.

        I hold an M.S. in Business Analytics from California State Polytechnic University, Pomona and a
        B.S. in Business Administration from California State University, Los Angeles.
    design:
      columns: '1'
  - block: resume-experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: false
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        LinkedIn: [harshitavallamsetty](https://www.linkedin.com/in/harshitavallamsetty/)  
        Location: San Jose, CA
    design:
      columns: '1'
---
