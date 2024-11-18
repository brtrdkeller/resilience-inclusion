---
title: Digital Accessibility Inclusion
subtitle: Capitalisation des savoirs de l'équipe ATI (Assistance Technique Inclusion)
seo_title:

primary_cta_page: "about"
secondary_cta_page: "projects"

posts_section_heading: Recent Posts
projects_section_heading: Projects

outputs:
  - html
  - json
  - search

disableKinds:
  - RSS
  - taxonomy
  - taxonomyTerm
  - accessibility
  
cascade:
- _target:
    path: /publication/**
  outputs:
    - html
    - print
    - presentation
- _target:
    path: /assessment/**
  outputs:
    - html
    - print
    - presentation
---
