---
type: PageLayout
title: Contact
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Let´s get in Touch
      color: text-dark
    subtitle: ''
    text: |+
      ## ***We're ready to help! Request your quote now!***

    actions:
      - type: Link
        label: Instagram
        altText: Instagram
        url: /gobranding-usa
        showIcon: true
        icon: instagram
        iconPosition: left
        style: secondary
        elementId: ''
      - type: Link
        label: Facebook
        altText: Facebook
        url: /
        showIcon: true
        icon: facebook
        iconPosition: left
        style: secondary
        elementId: ''
      - type: Link
        label: Send email
        altText: Play
        url: /
        showIcon: true
        icon: mail
        iconPosition: right
        style: secondary
        elementId: ''
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: Contact Us
      color: text-primary
    colors: bg-light-fg-dark
slug: /contact
seo:
  type: Seo
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create
  socialImage: /images/main-hero.jpg
  metaTags: []
---
