---
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Contact us
sections:
  - elementId: ''
    colors: colors-a
    backgroundSize: full
    title: Contact us
    text: |+
      We look forward to hearing feedback from you.

      SOLAROW
      Croatia
      10000 Zagreb
      E-Mail: contact.solarow@gmail.com

    form:
      type: FormBlock
      variant: variant-a
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: 'true'
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: 'true'
          width: 1/2
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          isRequired: false
          width: full
        - name: text
          label: Text
          hideLabel: false
          placeholder: Enter message
          isRequired: true
          width: full
          type: TextFormControl
        - name: description
          label: Description
          hideLabel: false
          placeholder: Please describe
          isRequired: false
          width: full
          type: TextareaFormControl
      submitLabel: Send Message
    media: null
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderColor: border-complementary
        borderWidth: 0
      title:
        textAlign: left
      text:
        textAlign: left
    type: ContactSection
layout: PageLayout
---
