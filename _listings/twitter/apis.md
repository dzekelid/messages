---
name: Twitter
x-slug: twitter
description: From breaking news and entertainment to sports and politics, get the
  full story with all the live commentary.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/266-twitter.jpg
x-kinRank: "9"
x-alexaRank: "12"
tags: Messages
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/twitter/apis.md
specificationVersion: "0.14"
apis:
- name: Twitter Get Sent Direct Messages
  x-api-slug: twitter
  description: return 20 most recent direct messages sent
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/266-twitter.jpg
  humanURL: https://twitter.com/
  baseURL: https://api.twitter.com//1.1//direct_messages/sent
  tags: Social,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/twitter/direct-messagessent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/twitter/direct-messagessent-get-openapi.md
- name: Twitter Show Direct Message
  x-api-slug: twitter
  description: returns a single direct message specified by an id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/266-twitter.jpg
  humanURL: https://twitter.com/
  baseURL: https://api.twitter.com//1.1//direct_messages/show
  tags: Social,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/twitter/direct-messagesshow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/twitter/direct-messagesshow-get-openapi.md
- name: Twitter Get Direct Messages
  x-api-slug: twitter
  description: return 20 most recent direct messages sent to user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/266-twitter.jpg
  humanURL: https://twitter.com/
  baseURL: https://api.twitter.com//1.1//direct_messages
  tags: Social,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/twitter/direct-messages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/twitter/direct-messages-get-openapi.md
- name: Twitter Remove Direct Message
  x-api-slug: twitter
  description: destroys direct messages specified in required ID
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/266-twitter.jpg
  humanURL: https://twitter.com/
  baseURL: https://api.twitter.com//1.1//direct_messages/destroy
  tags: Social,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/twitter/direct-messagesdestroy-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/twitter/direct-messagesdestroy-post-openapi.md
- name: Twitter Create Direct Message
  x-api-slug: twitter
  description: sends a new direct message to specified user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/266-twitter.jpg
  humanURL: https://twitter.com/
  baseURL: https://api.twitter.com//1.1//direct_messages/new
  tags: Social,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/twitter/direct-messagesnew-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/twitter/direct-messagesnew-post-openapi.md
- name: Twitter
  x-api-slug: twitter
  description: From breaking news and entertainment to sports and politics, get the
    full story with all the live commentary.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/266-twitter.jpg
  humanURL: https://twitter.com/
  baseURL: https://api.twitter.com//1.1
  tags: Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/messages/master/_listings/twitter/openapi.md
x-common:
- type: x--net-library
  url: https://tweetinvi.codeplex.com/
- type: x-advertising-development-kit
  url: https://docs.fabric.io/unity/mopub/overview.html
- type: x-android-sdk
  url: https://docs.fabric.io/android/fabric/overview.html
- type: x-apple-sdk
  url: https://docs.fabric.io/apple/fabric/overview.html
- type: x-application-management
  url: https://apps.twitter.com/
- type: x-application-only-authentication
  url: https://dev.twitter.com/oauth/application-only
- type: x-authentication
  url: https://dev.twitter.com/oauth
- type: x-authentication-overview
  url: https://dev.twitter.com/oauth/overview
- type: x-base
  url: https://api.twitter.com
- type: x-best-practices
  url: https://dev.twitter.com/overview/general
- type: x-beta
  url: https://docs.fabric.io/unity/beta/overview.html
- type: x-branding
  url: https://brand.twitter.com/
- type: x-branding
  url: https://dev.twitter.com/overview/terms/display-requirements
- type: x-branding
  url: https://about.twitter.com/company/brand-assets
- type: x-case-studies
  url: https://dev.twitter.com/overview/case-studies
- type: x-change-log
  url: https://dev.twitter.com/ads/overview/recent-changes
- type: x-code-libraries
  url: https://dev.twitter.com/overview/api/twitter-libraries
- type: x-coldfusion-library
  url: http://monkehtweet.riaforge.org/
- type: x-console
  url: http://dev.twitter.com/rest/tools/console
- type: x-crunchbase
  url: http://www.crunchbase.com/company/twitter
- type: x-crunchbase
  url: https://crunchbase.com/organization/twitter
- type: x-css-control
  url: https://dev.twitter.com/web/overview/css
- type: x-developer
  url: https://developer.twitter.com/
- type: x-blog
  url: https://dev.twitter.com/blog/
- type: x-blog-rss
  url: https://blog.twitter.com/api/blog.rss?name=developer
- type: x-documentation
  url: https://dev.twitter.com/overview/documentation
- type: x-email
  url: copyright@twitter.com
- type: x-embeddable
  url: https://dev.twitter.com/web/overview
- type: x-encryption
  url: https://dev.twitter.com/overview/api/tls
- type: x-blog
  url: https://blog.twitter.com/engineering
- type: x-blog-rss
  url: https://blog.twitter.com/api/blog.rss?name=engineering
- type: x-error-codes
  url: https://dev.twitter.com/overview/api/response-codes
- type: x-events
  url: https://dev.twitter.com/overview/events
- type: x-forum
  url: https://twittercommunity.com/
- type: x-forum
  url: https://twittercommunity.com/c/fabric
- type: x-geo-guidelines
  url: https://dev.twitter.com/overview/terms/geo-developer-guidelines
- type: x-github
  url: https://github.com/twitter
- type: x-go-library
  url: https://github.com/kurrik/twittergo
- type: x-internationalization
  url: https://dev.twitter.com/overview/general/adding-international-support-to-your-apps
- type: x-java-library
  url: https://www.github.com/twitter/hbc
- type: x-node-js-library
  url: https://github.com/BoyCook/TwitterJSClient
- type: x-oembed
  url: https://dev.twitter.com/web/embedded-timelines/oembed
- type: x-partners
  url: https://dev.twitter.com/overview/general/official-partner-program
- type: x-php-library
  url: https://github.com/abraham/twitteroauth
- type: x-pin-based-authorization
  url: https://dev.twitter.com/oauth/pin-based
- type: x-blog
  url: https://blog.twitter.com/
- type: x-blog-rss
  url: https://blog.twitter.com/api/blog.rss?name=company
- type: x-privacy
  url: https://twitter.com/privacy?lang=en
- type: x-python-library
  url: https://github.com/bear/python-twitter
- type: x-rate-limits
  url: https://dev.twitter.com/rest/public/rate-limiting
- type: x-rate-limits-chart
  url: https://dev.twitter.com/rest/public/rate-limits
- type: x-road-map
  url: https://dev.twitter.com/ads/overview/upcoming-changes
- type: x-ruby-library
  url: https://github.com/sferik/twitter
- type: x-schema
  url: https://dev.twitter.com/overview/api/entities-in-twitter-objects
- type: x-security
  url: https://dev.twitter.com/overview/general/security-best-practices
- type: x-statistics
  url: https://docs.fabric.io/unity/answers/overview.html
- type: x-status
  url: https://dev.twitter.com/overview/status
- type: x-streaming
  url: https://dev.twitter.com/streaming/overview
- type: x-support
  url: https://support.twitter.com/
- type: x-terms-of-service
  url: https://dev.twitter.com/overview/terms
- type: x-transparency-report
  url: https://transparency.twitter.com/
- type: x-twitter
  url: https://twitter.com/Twitter
- type: x-twitter
  url: https://twitter.com/twitterapi/
- type: x-twitter
  url: https://twitter.com/twittereng/
- type: x-website
  url: https://twitter.com/
- type: x-wordpress
  url: https://dev.twitter.com/web/wordpress
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---