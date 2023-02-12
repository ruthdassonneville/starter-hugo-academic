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
     # Social/Academic Networking
# For available icons, see: https://wowchemy.com/docs/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "/#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: mailto:ruth.dassonneville@umontreal.ca
  - icon: twitter
    icon_pack: fab
    link: https://twitter.com/r_dassonneville
    display:
      header: true
  - icon: graduation-cap # Alternatively, use `google-scholar` icon from `ai` icon pack
    icon_pack: fas
    link: https://scholar.google.ca/citations?user=H9tX4uwAAAAJ&hl=en&oi=ao
  - icon: github
    icon_pack: fab
    link: https://github.com/ruthdassonneville
  # Link to a PDF of your resume/CV.
  # To use: copy your resume to `static/uploads/resume.pdf`, enable `ai` icons in `params.yaml`,
  # and uncomment the lines below.
  # - icon: cv
  #  icon_pack: ai
  #  link: uploads/resume.pdf    
        
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
