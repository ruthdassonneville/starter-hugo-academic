---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Ruth Dassonneville
      image:
        filename: website-profile.jpg
      text: |-
        Associate professor, Université de Montréal  
        
        [Canada Research Chair in Electoral Democracy](https://www.chairedemocratie.com/)

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
      design:
      background:
        gradient_end: '#FFFFFF'
        gradient_start: '#FFFFFF'
        text_color_light: false
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:     
      
  - block: collection
    id: publications
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      columns: '2'
      view: card
---
