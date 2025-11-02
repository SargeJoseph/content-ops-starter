---
title: Pricing
slug: pricing
sections:
  - title:
      text: Open Source & Free
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Security tools for everyone
    text: >
      TraceConsole is completely free and open source. Access all features without restrictions, subscriptions, or hidden costs. Built by security professionals for security professionals.
    actions:
      - label: Get Started
        url: https://github.com/SargeJoseph/TraceConsole
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
  - title:
      text: Choose Your Setup
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: All features included
    plans:
      - title: Community Edition
        price: Free
        details: Forever
        description: >
          Perfect for individual analysts and small teams
        features:
          - Unlimited IP scanning
          - Multi-source threat intelligence
          - Automated firewall blocking
          - Event log analysis
          - VirusTotal integration
          - SQLite database
          - 90-day intelligent caching
        image:
          url: /images/abstract-feature1.svg
          altText: Community Edition
          type: ImageBlock
        actions:
          - label: Download
            url: https://github.com/SargeJoseph/TraceConsole
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: Enterprise Support
        price: Custom
        details: Professional services
        description: >
          For organizations requiring advanced support
        features:
          - All community features
          - Priority support
          - Custom integrations
          - Training sessions
          - Implementation assistance
          - SLA guarantees
          - Dedicated consulting
        image:
          url: /images/abstract-feature3.svg
          altText: Enterprise Support
          type: ImageBlock
        actions:
          - label: Contact Sales
            url: https://toilemaitre.com
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: PricingSection
seo:
  metaTitle: Pricing - Toilemaitre Security Tools
  metaDescription: >-
    Free and open source security forensics toolkit. No subscriptions, no hidden costs.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
