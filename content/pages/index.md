---
title: Home
layout: PageLayout
sections:
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-4
          - pb-0
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-d
    backgroundSize: inset
    title: Elevating conscience one at a time.
    subtitle: Investing in people that are co-creating for equitable world
    actions:
      - type: Button
        label: Get Started
        url: 'https://www.stackbit.com/'
        style: primary
        iconPosition: right
        icon: arrowRight
        showIcon: true
    backgroundImage:
      type: BackgroundImage
      url: /images/hero.webp
      backgroundSize: cover
      backgroundPosition: center
      opacity: 85
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-6
          - mb-0
        padding:
          - pt-20
          - pb-96
          - pr-12
          - pl-12
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
  - type: QuoteSection
    colors: colors-d
    quote: >
      Neutral tech investment firm. Our playbook is different we invest in ideas
      and philosophies that are open, simple, and sustainable.
      #BuildingOpenSocialCapital..[read more](/blog/what-is-neutral-tech/)
    name: Saransh Sharma
    title: Partner
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pr-4
          - pl-4
        justifyContent: center
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center
  - colors: colors-d
    elementId: ''
    title: Ok how does this work?
    subtitle: ''
    items:
      - type: FeaturedItem
        text: >+
          Discover a New Way to Invest with Our Neutral Tech Investment Firm


          Are you ready to make a difference with your investments? At our
          neutral tech investment firm, we prioritize businesses that align with
          our core axioms of equity, fairness, and transparency. By focusing on
          these principles, we can drive sustainable development and make a
          positive impact on society.

        actions:
          - type: Button
            label: Learn more
            showIcon: true
            icon: arrowRight
            url: /
            style: secondary
        styles:
          self:
            textAlign: left
        title: Collaboration
      - type: FeaturedItem
        title: Initiation
        text: >
          At our neutral tech investment firm, we take pride in fostering strong
          partnerships with businesses that share our values of equity,
          fairness, and transparency.


          Once a collaboration is established, we continue to support these
          businesses by providing them with the necessary resources and guidance
          to thrive and make a positive societal impact. 
        actions:
          - type: Button
            label: Learn more
            showIcon: true
            icon: arrowRight
            url: /
            style: secondary
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: Focused
        text: >+
          A detached oriented process that provides ample time to teams and
          businesses for building products and testing hypothesis in
          co-ordinated  groups. This means business are focused only on what
          they want to achieve with commnuities.


          *   Product market fit testing


          *   Support for further mentoring and expansion


          *   Community expansion

        actions:
          - type: Button
            label: Learn more
            showIcon: true
            icon: arrowRight
            url: /
            style: secondary
        styles:
          self:
            textAlign: left
    actions: []
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
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeaturedItemsSection
  - elementId: ''
    colors: colors-c
    variant: variant-a
    title: Our portfolio
    actions:
      - type: Link
        label: See all adventures
        url: /blog
        showIcon: true
        icon: arrowRight
    posts:
      - content/pages/blog/post-five.md
      - content/pages/blog/post-four.md
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
          - pb-48
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
      actions:
        justifyContent: flex-start
    type: FeaturedPostsSection
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    readMoreLinkLabel: Join adventure
    showAuthor: false
  - type: TextSection
    colors: colors-e
    variant: variant-a
    text: |+
      ## Find us on [Second.Exchange](https://second.exchange)

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
          - pt-36
          - pb-36
          - pr-4
          - pl-4
        justifyContent: center
      text:
        textAlign: center
  - type: FeatureHighlightSection
    colors: colors-d
    backgroundSize: full
    title: What is neutral tech?
    text: >
      Investing in people ,  ideas and projects that are fundamentally different
      and are observing sustainable goals. 
    actions:
      - type: Link
        label: Learn more
        url: /blog/what-is-neutral-tech/
        showIcon: true
        icon: arrowRight
    backgroundImage:
      type: BackgroundImage
      url: /images/hero-3.webp
      backgroundSize: cover
      backgroundPosition: center
      opacity: 90
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
          - pb-72
          - pr-4
          - pl-4
        justifyContent: flex-start
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: ContactSection
    colors: colors-d
    title: Want to invest with us?
    text: >
      We will connect you with one of our partner in your respective geography
      that will guide you the next steps.
    form:
      type: FormBlock
      elementId: sign-up-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: full
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: Submit
      styles:
        submitLabel:
          textAlign: center
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
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-4
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
addTitleSuffix: true
metaTags: []
---
