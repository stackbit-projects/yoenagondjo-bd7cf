---
title: Contact
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: >
      Construisons quelque chose de grand ensemble.


      Remplissezce formulaire de contact ou envoyez-moi un email à
      yoenagondjo@gmail.com.


      ***


      ## Ma position géographique


      ### GABON


      Ancienne Sobraga, Libreville


      (+241) 77 45 05 35


      [Get directions →](https://goo.gl/maps/eh6fn7JjMS4vYs337)
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nom
        default_value: Votre nom
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Votre adresse mail
        is_required: true
      - input_type: select
        name: sujet
        label: Quels services cherchez vous ?
        default_value: Sélectionnez s'il vous plaît
        options:
          - Conception de logo
          - Création de site web
          - Création d'une landing page
          - Conception de bannières publicitaires
          - lorem-ipsum
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
