---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-a
    title: Welcome to the future
    subtitle: 'Charge smart, worry less.'
    actions:
      - type: Link
        label: Learn More
        url: /solarpower-b1
        showIcon: true
        icon: arrowRight
        iconPosition: right
    media:
      type: ImageBlock
      url: /images/1647368293288.png
      altText: Image alt text
      caption: Image caption
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
          - pt-12
          - pb-28
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - elementId: ''
    colors: colors-a
    title: Need huge battery?
    text: >
      Big 100000mAh will charge any of your devices multiple times in a row.
      PowerBank with many ports to charge even more devices together so you
      won't need to charge separately. And rugged body will survive falls to
      ground.
    actions:
      - label: Learn more
        altText: ''
        url: /solarpower-m1
        showIcon: true
        icon: arrowRight
        iconPosition: right
        elementId: ''
        type: Link
    media:
      type: ImageBlock
      url: >-
        /images/99000mAh-Solar-Power-Bank-Large-Capacity-Portable-Charger-2USBcellphone-Battery-Outdoor-Waterproof-Power-Bank-for-Xiaomi.jpg_Q90.jpg_.webp
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
          - pb-6
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeatureHighlightSection
    badge:
      label: M1
      elementId: ''
      styles:
        self:
          textAlign: left
  - elementId: ''
    colors: colors-a
    title: Or easy portability?
    text: >
      Small body will make you forgot you are holding PowerBank in your hands or
      have in your pocket, and solid 5000mAh battery capacity will be enough to
      charge almost any phone from 0% to 100%.
    actions:
      - label: Learn more
        altText: ''
        url: /solarpower-p1
        showIcon: true
        icon: arrowRight
        iconPosition: right
        elementId: ''
        type: Link
    media:
      type: ImageBlock
      url: >-
        /images/NEW-RT-PINZHENG-Mini-Solar-Power-Bank-5000-10000mAh-Power-Bank-For-Phone-Powerbank-External-Spare.jpg_Q90.jpg_.png
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
          - pt-6
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeatureHighlightSection
    badge:
      label: P1
      elementId: ''
      styles:
        self:
          textAlign: left
  - colors: colors-a
    elementId: ''
    title: Why you should get SolarPower?
    subtitle: >-
      Some great features that will provide exactly the things you’re looking
      for.
    items:
      - type: FeaturedItem
        title: Ecofriendly
        text: >
          It's made of recycle and degradable materials what doesn't affect to
          the nature.
        featuredImage:
          url: /images/1460537.png
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
      - type: FeaturedItem
        title: Smarter
        text: >
          When the PowerBank is charged to the max, it will automatically stop
          charging to extend the battery.
        featuredImage:
          url: /images/2914281.png
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
      - type: FeaturedItem
        title: Focused
        text: >
          It is focused to the smartphone and tablet lines, no matter does it or
          doesn't support wireless charging.
        featuredImage:
          url: /images/1828178.png
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
    columns: 3
    enableHover: false
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
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-start
    type: FeaturedItemsSection
  - elementId: ''
    colors: colors-a
    backgroundSize: full
    title: Sign up today
    text: >
      Be notified about newest products, promotions, and other tech news from
      our website.
    form:
      type: FormBlock
      variant: variant-b
      elementId: sign-up-form
      action: /.netlify/functions/submission_created
      destination: contact.solarow@gmail.com
      fields:
        - type: EmailFormControl
          name: email
          placeholder: Your email
          isRequired: 'true'
          width: full
      submitLabel: Sign Up
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
          - pt-24
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
    type: ContactSection
socialImage: /images/SOLAROW (1).png
metaTitle: Home
metaDescription: Get the new PowerBank and say goodbye to 0%. Since 2022.
addTitleSuffix: true
metaTags: []
---
