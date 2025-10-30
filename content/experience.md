---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: features
    content:
      title: "TOEFL Scores"
      text: "September 2024"
      items:
        - name: "Reading"
          description: "28/30"
          icon: "bolt"
        - name: "Listening"
          description: "27/30"
          icon: "bolt"
        - name: "Speaking"
          description: "22/30"
          icon: "bolt"
        - name: "Writing"
          description: "26/30"
          icon: "bolt"
    design:
      columns: "2"
      background:
  - block: resume-awards
    content:
      title: Awards
      username: admin
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false

  
---
