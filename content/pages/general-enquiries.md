---
title: General enquiries
sections:
  - type: hero_section
    title: Deine Anfrage
    subtitle: Wir hören dir genau zu und sind für dich da!
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ## Anfragen


      Deine Anfrage wird mit höchster Priorität bearbeitet und an die
      entsprechenden Stellen weitergeleitet. Du bekommst schnellstmöglich eine
      Antwort 


      ## Datenschutz


      Zum Zweck der Bearbeitung werden wir deine Daten verarbeitung und nach
      Abschluss der Anfrage wieder löschen. 
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Name
        label: Name
        default_value: Dein Name
        is_required: true
      - input_type: email
        name: E-Mail Adresse
        label: Email
        default_value: Deine E-Mail Adresse
        is_required: true
      - input_type: select
        name: subject
        label: Betreff
        default_value: Bitte wähle aus
        options:
          - Hilfe & Support
          - Partnerschaft und Sponsoring
          - Spezielle Anfrage
        is_required: true
      - input_type: textarea
        name: message
        label: Deine Nachricht
        default_value: Hier kommt dein Text...
      - input_type: checkbox
        name: consent
        label: >-
          Ich bin damit einverstanden, dass mein Daten für die Beantwortung
          meiner Frage verarbeitet werden und im Anschluss wieder gelöscht wird.
        is_required: true
    submit_label: SENDEN
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
seo:
  title: General Enquiries
  description: This is the general enquiries page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: General Enquiries
      keyName: property
    - name: 'og:description'
      value: This is the general enquiries page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: General Enquiries
    - name: 'twitter:description'
      value: This is the general enquiries page
layout: advanced
---
