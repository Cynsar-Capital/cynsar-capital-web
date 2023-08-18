---
title: About
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
  - type: TextSection
    colors: colors-d
    variant: variant-a
    title: About our business
    text: "Cynsar Capital was founded in 2021 by Saransh, an entrepreneur with experience in building financial tools,\_ and Cici, a retired corporate finance attorney. Saransh, with his expertise in developing research-oriented businesses, handles the key operations. Cici, with her experience as a financial lawyer, serves as an advisor and initial investor.\n\nCynsar Capital has dedicated considerable time and resources to conduct extensive internal research in collaboration with our partners. This investment has allowed us to gain a deep understanding of market size and emerging opportunities. Based on our findings, we have identified specific areas of management in which we aspire to take the lead and offer innovative solutions.\n\n![](/images/Sketches%2010.png)\n\n> Our premise is straightforward: In the Global South, only a small percentage of businesses manage to shine in their early stages compared to the volume of early-stage funding available in the Global North. Consider that out of approximately 200,000 startups in the Global South, a mere 2% garner early-stage support. Imagine the potential if, through our steadfast dedication, we could elevate this number to support even 5% of these startups. By doing so, we'd be tapping into a vast reservoir of overlooked opportunities and unparalleled growth. The ripple effect would be truly transformative.\n\n"
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
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - elementId: ''
    colors: colors-b
    quote: >
      We serve as a mental support system, akin to therapists emotional anchors,
      allowing entrepreneurs to express themselves freely. This fosters a
      healthier business development process and facilitates more fruitful deals
      throughout their journey.
    backgroundImage:
      url: /images/bg.webp
      opacity: 70
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
          - pt-96
          - pb-10
          - pl-4
          - pr-4
        justifyContent: center
      quote:
        textAlign: left
      name:
        fontWeight: '400'
        fontStyle: normal
        textAlign: left
      title:
        fontWeight: '400'
        fontStyle: normal
        textAlign: left
    type: QuoteSection
  - elementId: ''
    variant: variant-c
    colors: colors-c
    title: Our Team
    subtitle: >-
      We’re a group of friends, who love exploring the world and sharing our
      experiences with the world.
    people:
      - content/data/team/desmond-eagle.json
      - content/data/team/hugh-saturation.json
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
          - pb-72
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedPeopleSection
  - type: ContactSection
    colors: colors-d
    title: Join our friendship?
    text: >
      We will notify you every time when we are in your neighborhood so that we
      can meet in person and let us know

       
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
      submitLabel: Submit form
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
          - ml-4
          - mr-4
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
---
