---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |+
      Pentru a ma contacta completeaza acest formular.

    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nume
        default_value: Numele tau
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Adresa ta de email
        is_required: true
      - input_type: select
        name: subiect
        label: Subiect
        default_value: Selecteaza
        options:
          - Eroare pe site
          - Sponsorizare
          - Altele
      - input_type: textarea
        name: message
        label: Mesaj
        default_value: Mesajul tau
      - input_type: checkbox
        name: consent
        label: >-
          Inteleg ca acest formular salveaza datele mele pentru a putea fi
          contactat inapoi.
    submit_label: Trimite
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
