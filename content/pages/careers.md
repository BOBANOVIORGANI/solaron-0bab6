---
title: Careers
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-h
    title: About us
    subtitle: Everything about team SOLAROW.
    media:
      type: ImageBlock
      url: /images/shutterstock_737994433.png
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - elementId: ''
    colors: colors-h
    quote: >+
      ## Being part of this team has been incredible. We’ve fill each other’s
      gaps, and helping each other.

    name: Team
    title: SOLAROW team members
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-36
        justifyContent: center
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center
    type: QuoteSection
  - elementId: ''
    colors: colors-a
    images:
      - type: ImageBlock
        url: /images/programming-team-content.png
        altText: People in the meeting room
      - type: ImageBlock
        url: /images/graphic-design-team-3-1024x536.png
        altText: People in the meeting room
    spacing: 3
    columns: 2
    aspectRatio: '1:1'
    imageSizePx: 400
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
          - pt-24
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
    type: MediaGallerySection
  - colors: colors-a
    elementId: ''
    title: Team roles
    jobLists:
      - type: JobList
        title: CEO
        items:
          - type: JobListItem
            title: Director of the company
            location: Marin Golub
            text: >
              CEO and founder of SOLAROW. Born in Croatia, small country in
              Europe. He managed to make a company with just 14 years. Now he is
              indebted for everything what is happening.
            actions: []
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-32
          - pb-60
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: center
    type: JobsSection
  - elementId: contact-form
    colors: colors-f
    backgroundSize: inset
    title: Didn't found what you wanted to?
    text: >
      If happen that you are not satisfied or didn't find answer for your
      question, feel free to contact us.
    form:
      type: FormBlock
      variant: variant-a
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: contact.solarow@gmail.com
      fields:
        - type: TextFormControl
          name: first-name
          label: Your first name
          hideLabel: true
          placeholder: First name
          isRequired: false
          width: 1/2
        - type: TextFormControl
          name: last-name
          label: Your last name
          hideLabel: true
          placeholder: Last name
          isRequired: false
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Your email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
        - type: TextFormControl
          name: address
          label: Your address
          hideLabel: true
          placeholder: Address
          isRequired: false
          width: full
      submitLabel: Submit
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-24
          - mb-10
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: center
      text:
        textAlign: center
    type: ContactSection
---
