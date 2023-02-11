---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: publications
    id: publications
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: projects
    content:
      title: Research Projects
    design:
      columns: '2'
      view: citation
  - block: teaching
    content:
      title: Teaching
    design:
      columns: '2'
      view: citation    
  - block: chair
    content:
      title: Canada Research Chair in Electoral Democracy
    design:
      columns: '2'
      view: citation        
---
