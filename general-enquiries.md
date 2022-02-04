---
title: General Enquiries
sections:
  - type: form_section
    content: >
      ### Get in touch


      Have a question? Send us a note using the form and we will be in touch
      soon.
    content_align: center
    form_position: bottom
    form_width: fourty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Mentorship
          - Mestara Berdaya
          - Sponsorship
          - General inquiry
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
        is_required: true
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
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
