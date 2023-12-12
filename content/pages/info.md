---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >-
      ## Hello! My name is Kaeleigh Wren. I am thrilled to welcome you to my computer science portfolio. As a junior computer science student at Montana State University, I am passionate about exploring the fascinating world of technology and its limitless potential to solve complex problems and enhance our lives. My journey in computer science began in a rather unexpected way—working at the St. James Healthcare hospital lab. During my time at the hospital lab, I had the opportunity to interact closely with the lab technology and the Epic computer system, which serves as a backbone for managing patient data and improving healthcare work flow. Witnessing the power of technology in a healthcare setting sparked my curiosity and ignited a desire to delve deeper into the world of computer science.

    media:
      type: ImageBlock
      url: \images\aboutme.JPG
      altText: aboutme
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection

  - type: MediaGallerySection
    colors: colors-f

  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: Github
            url: 'https://github.com/kaeastic'
        styles:
          self:
            textAlign: left

      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/in/kaeleigh-wren-173b80250/'
        styles:
          self:
            textAlign: left

      - type: FeaturedItem
        actions:
          - type: Link
            label: Handshake
            url: 'https://montana.joinhandshake.com/stu/users/36917826'
        styles:
          self:
            textAlign: left

    columns: 3
    spacingX: 120
    spacingY: 0
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
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
        textAlign: left
    subtitle: 'You can find me here:'
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: 'Python'
      - type: Label
        label: Adobe Creative Cloud
      - type: Label
        label: Microsoft Office
      - type: Label
        label: Next.js
      - type: Label
        label: Stackbit
      - type: Label
        label: Java
      - type: Label
        label: C+
      - type: Label
        label: HTML/CSS
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [kaeleigh.wren@student.montana.edu](mailto:kaeleigh.wren@student.montana.edu)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: |-
          **Current**

          * Grocery at Co-Op(Bozeman, MT)
          * Event Staff at the Rialto(Bozeman, MT)

          **2019-2021**

          * Phlebotomist at St. James Healthcare(Butte, MT)

          **2018**

          * Psych Tech at North Mississippi Medical Center (Tupelo, MS)

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
      - type: FeaturedItem
        subtitle: 'Education:'
        text: |-
          **2019-Current**
           
          * Major change to BS in Computer Science:Professional Option, Montana State University

          **2018-2019**

          * Nursing prerequisites, Montana Tech

          **2016-2017**

          * Phlebotomy certificate at Itawaba Community College

          **2015**

          * Graduated from Saltillo High School
        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
    columns: 2
    spacingX: 60
    spacingY: 60
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
          - pt-8
          - pb-8
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
        textAlign: left

  - type: ContactSection

    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
