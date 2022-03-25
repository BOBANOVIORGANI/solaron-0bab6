---
metaTitle: Contact us
metaDescription: Contact and our support team will reply as soon as possible. Since 2022.
addTitleSuffix: true
socialImage: /images/SOLAROW (1)-5074eeb3.png
metaTags: []
title: Contact us
sections:
  - elementId: ''
    colors: colors-a
    backgroundSize: full
    title: Contact us
    text: |+
      We look forward to hearing feedback from you.

      *   SOLAROW

      *   Croatia

      *   10000 Zagreb

      *   E-Mail: contact.solarow@gmail.com

    form:
      type: FormBlock
      variant: variant-a
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: contact.solarow@gmail.com
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
          placeholder: Enter your email
          isRequired: 'true'
          width: 1/2
        - name: description
          label: Description
          hideLabel: false
          placeholder: Please describe
          isRequired: false
          width: full
          type: TextareaFormControl
        - type: CheckboxFormControl
          name: updates
          label: Subscribe to newsletter
          isRequired: false
          width: full
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
