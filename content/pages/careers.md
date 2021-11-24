---
title: Careers
layout: PageLayout
sections:
  
  - elementId: ''
    colors: colors-f
    title: Get early access
    text: >-
      Sign up your team today to be the first to try out our new product to
      increase your team's productivity.
    form:
      type: FormBlock
      elementId: sign-up-form
      action: /.netlify/functions/submission_created
      destination: ''
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
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
    type: ContactSection
  - colors: colors-a
    elementId: ''
    title: Convinced? check out these open roles
    items:
      - type: FeaturedItem
        title: Product
        text: >
          Director of product managment


          **San Francisco**


          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
        styles:
          title:
            textAlign: left
          text:
            textAlign: left
        actions:
          - label: Apply
            altText: Apply
            url: /
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: link
            elementId: ''
            type: Link
      - type: FeaturedItem
        title: Engineering
        text: >
          Head of eng


          **San Francisco**


          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
        styles:
          title:
            textAlign: left
          text:
            textAlign: left
        actions:
          - label: Apply
            altText: Apply
            url: /
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: link
            elementId: ''
            type: Link
      - type: FeaturedItem
        title: Product
        text: >
          Director of product managment


          **San Francisco**


          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
        styles:
          title:
            textAlign: left
          text:
            textAlign: left
        actions:
          - label: Apply
            altText: Apply
            url: /
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: link
            elementId: ''
            type: Link
      - type: FeaturedItem
        title: Product
        text: >
          Director of product managment


          **San Francisco**


          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
        styles:
          title:
            textAlign: left
          text:
            textAlign: left
        actions:
          - label: Apply
            altText: Apply
            url: /
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: link
            elementId: ''
            type: Link
    columns: 1
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
---
