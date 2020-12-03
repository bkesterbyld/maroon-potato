---
title: Beta Signup
sections:
  - type: hero_section
    title: Be a part of our beta
    subtitle: Coming in Q1 2021
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >-
      ### It's Free

      We'd love to help you with some pet project or anything you can think of.
      In exchange for your use and feedback we'll put you on our swag list (when
      we have enough of it) and anything you build up to 500,000 rows of data
      you can keep running forever, no charge. 

      ### Privacy

      We never sell information to third parties. Period. 
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
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
          - I want to join the beta
          - I have questions
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
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
template: advanced
---
