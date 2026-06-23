---
title: 'Academic CV'
date: 2023-10-24
type: landing

design:
  spacing: '4rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: markdown
    content:
      title: Academic CV
      text: |-
        Research experience, selected skills, service, awards, and education are summarized below. Download the latest PDF version: [Wenbo Zhang Academic CV](/uploads/resume.pdf).
    design:
      columns: '1'
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills
      username: me
  - block: resume-awards
    content:
      title: Awards
      username: me
  - block: markdown
    id: service
    content:
      title: Academic Service
      text: |-
        - Reviewer for ACM IMWUT / UbiComp and AAAI.
        - Contributed to the preparation and organization of WearAgent 2026: The 1st International Workshop on Interactive AI for Personal Wearable Agents, ACM UbiComp / ISWC 2026.
        - Invited panelist, "Impact, Risks, and Security/Privacy in Ubiquitous Computing Research," ACM UbiComp / ISWC 2025.
        - Student Volunteer, ACM UbiComp / ISWC 2025, Helsinki, Finland.
    design:
      columns: '1'
  - block: resume-languages
    content:
      title: Languages
      username: me
---
