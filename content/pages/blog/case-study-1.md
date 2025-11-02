---
title: Case study 1
slug: case-study-1
date: '2022-01-05'
excerpt: >-
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante lorem,
  tincidunt ac leo efficitur, feugiat tempor odio. Curabitur at auctor sapien.
  Etiam at cursus enim. Suspendisse sed augue tortor. Nunc eu magna vitae lorem
  pellentesque fermentum. Sed in facilisis dui.
featuredImage:
  url: /images/img-placeholder.svg
  altText: Case study 1
  styles:
    self:
      borderRadius: large
  type: ImageBlock
bottomSections:
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - items:
      - title: About Company
        tagline: This is the tagline
        subtitle: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Curabitur at
          auctor sapien.
        image:
          url: /images/telus-logo.svg
          altText: Company logo
          styles:
            self:
              margin:
                - ml-3
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pl-6
              - pb-6
              - pr-6
            textAlign: left
            borderColor: border-neutralAlt
            borderStyle: none
            borderWidth: 0
            borderRadius: none
            flexDirection: row
        type: FeaturedItem
    variant: small-list
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mb-20
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
isFeatured: true
colors: bg-light-fg-dark
styles:
  self:
    padding:
      - pt-5
      - pl-5
      - pb-5
      - pr-5
    textAlign: center
    borderColor: border-light
    borderStyle: none
    borderWidth: 0
    borderRadius: none
    flexDirection: col
type: PostLayout
---

When a mid-sized financial firm noticed unusual outbound connections from a critical server, their security team turned to TraceConsole for answers. Within minutes, TraceConsole parsed Windows event logs, correlated suspicious IPs with threat intelligence feeds, and flagged two connections to known malware hosts.

> "TraceConsole’s automated IP reputation checks and firewall blocking let us contain the threat before any data was exfiltrated. The forensic artifact collection helped us understand how the attack started."
>
> _By Clara White - VP of Security_

The team used TraceConsole’s CLI to extract Amcache and Prefetch artifacts, revealing a malicious executable launched via a scheduled task. Automated firewall rules blocked further outbound traffic, and the audit logs provided a clear timeline for incident reporting.

![](/images/img-placeholder.svg)

TraceConsole’s integration with VirusTotal and AbuseIPDB gave the team confidence in their response, and the SQLite cache ensured no duplicate API calls during the investigation. The incident was resolved in under an hour, with full documentation for compliance.
