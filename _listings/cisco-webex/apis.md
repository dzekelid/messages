---
name: Cisco WebEx
x-slug: cisco-webex
description: Cisco Webex is the leading enterprise solution for video conferencing
  & web conferencing today. This secure software-based platform for video & audio
  conferencing, group messaging & webinars helps organizations be more productive.Participants
  can join ...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
x-kinRank: "7"
x-alexaRank: "632"
tags: Messages
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/apis.md
specificationVersion: "0.14"
apis:
- name: Webex Teams Admin API - List Events (new messages)
  x-api-slug: events-get
  description: |-
    List events in your organization. Several query parameters are available to filter the response.
    Long result sets will be split into pages.

    https://developer.webex.com/endpoint-events-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/events-get-openapi.md
- name: Webex Teams API - List messages
  x-api-slug: messages-get
  description: "Lists all messages in a room. If present, includes the associated
    media content attachment for each message.\r\n\r\nThe list sorts the messages
    in descending order by creation date.\r\n\r\nhttps://developer.webex.com/endpoint-messages-get.html"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-get-openapi.md
- name: Webex Teams API - Get message details
  x-api-slug: messages-message-get
  description: |-
    Shows details for a message, by message ID.

    Specify the message ID in the messageId parameter in the URI.

    https://developer.webex.com/endpoint-messages-messageId-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-message-get-openapi.md
- name: Webex Teams API - Delete a message
  x-api-slug: messages-message-delete
  description: |-
    Deletes a message, by message ID.

    Specify the message ID in the messageId parameter in the URI.

    https://developer.webex.com/endpoint-messages-messageId-delete.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-message-delete-openapi.md
- name: Webex Teams API - Create a message (html)
  x-api-slug: messages-post
  description: |-
    HTML is not officially supported by the API, but will work in some cases

    To get more info about message formatting, check https://developer.ciscospark.com/formatting-messages.html

    https://developer.webex.com/endpoint-messages-post.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-post-openapi.md
- name: Webex Teams API - Create a webhook (messages/created)
  x-api-slug: webhooks-post
  description: |-
    Creates a webhook for messages/created event.

    Note that you'll need to change the requestb.in URI to your own to see the webhook in action.

    https://developer.webex.com/endpoint-webhooks-post.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/webhooks-post-openapi.md
- name: Webex Teams API - Get message details
  x-api-slug: messages-message-get
  description: |-
    Shows details for a message, by message ID.

    Specify the message ID in the messageId parameter in the URI.

    https://developer.webex.com/endpoint-messages-messageId-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-message-get-openapi.md
- name: Webex Teams API - Get message details
  x-api-slug: messages-message-get
  description: |-
    Shows details for a message, by message ID.

    Specify the message ID in the messageId parameter in the URI.

    https://developer.webex.com/endpoint-messages-messageId-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-message-get-openapi.md
- name: Webex Teams API - Delete a message
  x-api-slug: messages-message-delete
  description: |-
    Deletes a message, by message ID.

    Specify the message ID in the messageId parameter in the URI.

    https://developer.webex.com/endpoint-messages-messageId-delete.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-message-delete-openapi.md
- name: Webex Teams API - Delete a message
  x-api-slug: messages-message-delete
  description: |-
    Deletes a message, by message ID.

    Specify the message ID in the messageId parameter in the URI.

    https://developer.webex.com/endpoint-messages-messageId-delete.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-message-delete-openapi.md
- name: Webex Teams API - Create a message (html)
  x-api-slug: messages-post
  description: |-
    HTML is not officially supported by the API, but will work in some cases

    To get more info about message formatting, check https://developer.ciscospark.com/formatting-messages.html

    https://developer.webex.com/endpoint-messages-post.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-post-openapi.md
- name: Webex Teams API - Create a message (html)
  x-api-slug: messages-post
  description: |-
    HTML is not officially supported by the API, but will work in some cases

    To get more info about message formatting, check https://developer.ciscospark.com/formatting-messages.html

    https://developer.webex.com/endpoint-messages-post.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-post-openapi.md
- name: Webex Teams API - Create a message (html)
  x-api-slug: messages-post
  description: |-
    HTML is not officially supported by the API, but will work in some cases

    To get more info about message formatting, check https://developer.ciscospark.com/formatting-messages.html

    https://developer.webex.com/endpoint-messages-post.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-post-openapi.md
- name: Webex Teams API - Create a message (html)
  x-api-slug: messages-post
  description: |-
    HTML is not officially supported by the API, but will work in some cases

    To get more info about message formatting, check https://developer.ciscospark.com/formatting-messages.html

    https://developer.webex.com/endpoint-messages-post.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-post-openapi.md
- name: Webex Teams API - Delete a message
  x-api-slug: messages-message-delete
  description: |-
    Deletes a message, by message ID.

    Specify the message ID in the messageId parameter in the URI.

    https://developer.webex.com/endpoint-messages-messageId-delete.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-message-delete-openapi.md
- name: Webex Teams API - Delete a message
  x-api-slug: messages-message-delete
  description: |-
    Deletes a message, by message ID.

    Specify the message ID in the messageId parameter in the URI.

    https://developer.webex.com/endpoint-messages-messageId-delete.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-message-delete-openapi.md
- name: Webex Teams API - Get message details
  x-api-slug: messages-message-get
  description: |-
    Shows details for a message, by message ID.

    Specify the message ID in the messageId parameter in the URI.

    https://developer.webex.com/endpoint-messages-messageId-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-message-get-openapi.md
- name: Webex Teams API - Get message details
  x-api-slug: messages-message-get
  description: |-
    Shows details for a message, by message ID.

    Specify the message ID in the messageId parameter in the URI.

    https://developer.webex.com/endpoint-messages-messageId-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/cisco-webex/messages-message-get-openapi.md
x-common:
- type: x-postman-collection
  url: https://app.getpostman.com/run-collection/1f5e101d8290a5303c90
- type: x-api-gallery
  url: http://cisco.unity.connection.messaging.interface.api.gallery.streamdata.io
- type: x-api-stack
  url: http://cisco.webex.stack.network
- type: x-blog
  url: http://blogs.webex.com/
- type: x-blog-rss
  url: http://blogs.webex.com/webex_interactions/index.rdf
- type: x-crunchbase
  url: https://crunchbase.com/organization/webex-communications
- type: x-crunchbase
  url: http://www.crunchbase.com/company/webex
- type: x-postman-collection
  url: https://app.getpostman.com/run-collection/0aa22af74405f82086d4
- type: x-twitter
  url: https://twitter.com/webex
- type: x-developer
  url: https://developer.webex.com/
- type: x-website
  url: https://webex.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---