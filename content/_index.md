---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Ciberseguridad y <br> Ética Digital  en la Formación Docente
      subtitle: '(PID2023-148867OB-I00)'
      image:
        filename: welcome.jpg
      text: |
        (PID2023-148867OB-I00)
        <br>  
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        La capacitación en **ciberseguridad y ética digital** es esencial para que los docentes enseñen y actúen de forma segura y responsable en el entorno digital. Esto contribuye a una sociedad más competente y protegida.

        Este proyecto de investigación busca fortalecer las competencias digitales del profesorado de primaria mediante un **simulador virtual basado en inteligencia artificial**. Para ello, se analizará el nivel actual de conocimiento y los hábitos digitales del profesorado a través de encuestas, entrevistas y grupos focales.

        El objetivo es mejorar la seguridad digital, fomentar el comportamiento ético en línea y aportar al desarrollo económico mediante una fuerza laboral mejor preparada.
    design:
      columns: '1'
      # background:
      #   image: 
      #     filename: coders.jpg
      #     filters:
      #       brightness: 1
      #     parallax: false
      #     position: center
      #     size: cover
      #     text_color_light: true
      # spacing:
      #   padding: ['20px', '0', '20px', '0']
      # css_class: fullscreen
  
  - block: collection
    content:
      title: Últimas Noticias
      subtitle:
      text:
      count: 5
      filters:
        # author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Últimas Publicaciones
      text: ""
      count: 3
      filters:
        folders:
          - publication
        # publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Conoce al equipo →" %}}
    design:
      columns: '1'
---
