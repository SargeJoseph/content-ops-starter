title: Case study 2
slug: case-study-2
date: '2025-02-16'
excerpt: >-
A healthcare provider used TraceConsole to audit and update Windows Firewall rules across hundreds of endpoints, improving visibility and automating threat response for compliance and security.
featuredImage:
url: /images/img-placeholder.svg
altText: Case study 2
styles:
self:
borderRadius: x-large
type: ImageBlock
bottomSections:

- title: Divider
  colors: bg-light-fg-dark
  styles:
  self:
  padding: - pt-7 - pl-7 - pb-7 - pr-7
  type: DividerSection
- items: - title: About Company
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
  margin: - ml-3
  type: ImageBlock
  colors: bg-light-fg-dark
  styles:
  self:
  padding: - pt-6 - pl-6 - pb-6 - pr-6
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
  margin: - mb-20
  padding: - pt-0 - pl-0 - pb-0 - pr-0
  justifyContent: center
  subtitle:
  textAlign: center
  type: FeaturedItemsSection
  isFeatured: true
  colors: bg-light-fg-dark
  styles:
  self:
  padding: - pt-5 - pl-5 - pb-5 - pr-5
  textAlign: center
  borderColor: border-light
  borderStyle: none
  borderWidth: 0
  borderRadius: none
  flexDirection: col
  type: PostLayout

---

A large healthcare provider needed to audit Windows Firewall rules across hundreds of endpoints. Using TraceConsole, their IT team exported and analyzed all firewall rules, identifying outdated and risky configurations in minutes.

![](/images/img-placeholder.svg)

TraceConsole’s automated rule tracking and change history made it easy to spot recent modifications and correlate them with security events. The team used the CLI to query rules by port and IP, then applied batch updates to block known threats.

> "TraceConsole’s firewall management and audit logs gave us visibility we never had before. We could finally track every change and respond quickly to new risks."
>
> _By Gordon Red - Director of IT_

With scheduled scans and SQLite caching, the provider reduced manual review time by 70%. The integration with AbuseIPDB and VirusTotal ensured all blocks were based on up-to-date threat intelligence. Compliance reporting was simplified, and the team now runs automated audits monthly.
