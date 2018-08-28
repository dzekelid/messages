---
name: Spire Global
x-slug: spire-global
description: Spire Global, Inc. is an American private company specializing in data
  gathered from a network of small satellites.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spire-logo.png
x-kinRank: "7"
x-alexaRank: "557670"
tags: Messages
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/spire-global/apis.md
specificationVersion: "0.14"
apis:
- name: Spire API - All Messages from Date/Time Window
  x-api-slug: messages-get
  description: |-
    Returns all messages with a timestamp greater than `received_after` and timestamp less than `received_before`.
    Query can also be used without the `received_before` parameter.
    Timestamp must be within the past 7 days.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spire-logo.png
  humanURL: https://spire.com
  baseURL: https://ais.spire.com//
  tags: Satellites, SaaS, Enterprise, Technology, Marine, Weather, Aviation, Shipping,
    General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/spire-global/messages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/spire-global/messages-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://spectrocoin.api.gallery.streamdata.io
- type: x-api-stack
  url: http://spire.global.stack.network
- type: x-blog
  url: https://spire.com/insights/
- type: x-crunchbase
  url: https://crunchbase.com/organization/nanosatisfi
- type: x-developer
  url: https://spire.com/contact/developer-portal/
- type: x-email
  url: legal@spire.com
- type: x-twitter
  url: https://twitter.com/SpireGlobal
- type: x-website
  url: https://spire.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---