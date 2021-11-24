---
title: Careers
layout: PageLayout
sections:
  - colors: colors-c
    elementId: ''
    title: Gallery
    subtitle: This is the subtitle
    images:
      - type: ImageBlock
        url: 'https://assets.stackbit.com/components/images/default/image-1.jpeg'
        altText: Media gallery image
        caption: Image caption
      - type: ImageBlock
        url: 'https://assets.stackbit.com/components/images/default/image-2.jpeg'
        altText: Media gallery image
        caption: Image caption
      - type: ImageBlock
        url: 'https://assets.stackbit.com/components/images/default/image-3.jpeg'
        altText: Media gallery image
        caption: Image caption
      - type: ImageBlock
        url: 'https://assets.stackbit.com/components/images/default/image-4.jpeg'
        altText: Media gallery image
        caption: Image caption
    spacing: 1
    columns: 4
    aspectRatio: '16:9'
    imageSizePx: 300
    showCaption: true
    enableHover: true
    styles:
      self:
        width: full
        height: auto
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
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
    type: MediaGallerySection
  - elementId: ''
    variant: variant-b
    colors: colors-f
    title: Latest news
    subtitle: Latest blog posts section example
    actions:
      - type: Button
        label: View All
        altText: View All Posts
        url: /blog
        style: primary
    showRecent: true
    recentCount: 3
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
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: LatestPostsSection
  - elementId: ''
    colors: colors-h
    title: Love where you work
    subtitle: ''
    text: >-
      One platform, one community, getting to the bottom line of everything
      employment.  Figure out your benefits, practice for interviews, get
      mentored, help peers, get helped in return.
    actions:
      - type: Button
        label: Sign Up
        url: /
        style: primary
      - type: Link
        label: Learn More
        url: /
    media:
      type: ImageBlock
      url: /images/hero-1.png
      altText: Hero image
    backgroundImage: {}
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
          - pb-12
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
    type: HeroSection
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
