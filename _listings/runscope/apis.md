---
name: Runscope
x-slug: runscope
description: API performance monitoring. Everything is going to be 200 OK
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1752-runscope.jpg
x-kinRank: "9"
x-alexaRank: "125183"
tags: Messages
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/runscope/apis.md
specificationVersion: "0.14"
apis:
- name: Runscope Delete Buckets Messages
  x-api-slug: runscope
  description: Clear a bucket (remove all messages).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1752-runscope.jpg
  humanURL: http://runscope.com
  baseURL: https://api.runscope.com////buckets/{bucketKey}/messages
  tags: Buckets, Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/runscope/bucketsbucketkeymessages-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/runscope/bucketsbucketkeymessages-delete-openapi.md
- name: Runscope Get Buckets Messages
  x-api-slug: runscope
  description: Retrieve a list of messages in a bucket
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1752-runscope.jpg
  humanURL: http://runscope.com
  baseURL: https://api.runscope.com////buckets/{bucketKey}/messages
  tags: Buckets, Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/runscope/bucketsbucketkeymessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/runscope/bucketsbucketkeymessages-get-openapi.md
- name: Runscope Add Buckets Messages
  x-api-slug: runscope
  description: Create a message
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1752-runscope.jpg
  humanURL: http://runscope.com
  baseURL: https://api.runscope.com////buckets/{bucketKey}/messages
  tags: Buckets, Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/runscope/bucketsbucketkeymessages-post-openapi.md
- name: Runscope Get Buckets Messages Message
  x-api-slug: runscope
  description: Retrieve the details for a single message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1752-runscope.jpg
  humanURL: http://runscope.com
  baseURL: https://api.runscope.com////buckets/{bucketKey}/messages/{messageId}
  tags: Buckets, Messages, Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/runscope/bucketsbucketkeymessagesmessageid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/runscope/bucketsbucketkeymessagesmessageid-get-openapi.md
- name: Runscope
  x-api-slug: runscope
  description: API performance monitoring. Everything is going to be 200 OK
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1752-runscope.jpg
  humanURL: http://runscope.com
  baseURL: https://api.runscope.com//
  tags: Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/runscope/openapi.md
x-common:
- type: x-base-url
  url: https://api.runscope.com
- type: x-blog
  url: http://blog.runscope.com/
- type: x-blog-rss
  url: http://blog.runscope.com/posts?format=rss
- type: x-crunchbase
  url: https://crunchbase.com/organization/runscope
- type: x-crunchbase
  url: http://www.crunchbase.com/company/runscope
- type: x-developer
  url: https://www.runscope.com/docs/api
- type: x-email
  url: sales@runscope.com
- type: x-email
  url: press@runscope.com
- type: x-email
  url: help@runscope.com
- type: x-email
  url: dmca@runscope.com
- type: x-github
  url: https://github.com/Runscope
- type: x-openapi-spec--authoritative
  url: https://raw.githubusercontent.com/Runscope/runscope-api-examples/master/schemas/runscope-swagger.json
- type: x-pricing
  url: https://www.runscope.com/pricing-and-plans
- type: x-privacy
  url: https://www.runscope.com/privacy
- type: x-status
  url: http://status.runscope.com/
- type: x-support
  url: https://www.runscope.com/support
- type: x-terms-of-service
  url: https://www.runscope.com/terms
- type: x-twitter
  url: https://twitter.com/Runscope
- type: x-website
  url: http://runscope.com
- type: x-website
  url: https://www.runscope.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---