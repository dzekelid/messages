---
swagger: "2.0"
x-collection-name: Slack
x-complete: 0
info:
  title: Slack Get Permalink
  description: Retrieve a permalink URL for a specific extant message
  version: 1.0.3
host: slack.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /chat.delete:
    post:
      summary: Delete Message
      description: Deletes a message.
      operationId: chat_delete
      x-api-path-slug: chat-delete-post
      parameters:
      - in: formData
        name: as_user
        description: Pass true to delete the message as the authed user with `chat:write:user`
          scope
      - in: formData
        name: channel
        description: Channel containing the message to be deleted
      - in: header
        name: token
        description: Authentication token
      - in: formData
        name: ts
        description: Timestamp of the message to be deleted
      responses:
        200:
          description: OK
      tags:
      - Messages
  /chat.unfurl:
    post:
      summary: Unfurl Message
      description: Provide custom unfurl behavior for user-posted URLs
      operationId: chat_unfurl
      x-api-path-slug: chat-unfurl-post
      parameters:
      - in: formData
        name: channel
        description: Channel ID of the message
      - in: header
        name: token
        description: Authentication token
      - in: formData
        name: ts
        description: Timestamp of the message to add unfurl behavior to
      - in: formData
        name: unfurls
        description: URL-encoded JSON map with keys set to URLs featured in the the
          message, pointing to their unfurl message attachments
      - in: formData
        name: user_auth_message
        description: Provide a simply-formatted string to send as an ephemeral message
          to the user as invitation to authenticate further and enable full unfurling
          behavior
      - in: formData
        name: user_auth_required
        description: Set to `true` or `1` to indicate the user must install your Slack
          app to trigger unfurls for this domain
      - in: formData
        name: user_auth_url
        description: Send users to this custom URL where they will complete authentication
          in your app to fully trigger unfurling
      responses:
        200:
          description: OK
      tags:
      - Messages
  /chat.getPermalink:
    get:
      summary: Get Permalink
      description: Retrieve a permalink URL for a specific extant message
      operationId: chat_getPermalink
      x-api-path-slug: chat-getpermalink-get
      parameters:
      - in: query
        name: channel
        description: The ID of the conversation or channel containing the message
      - in: query
        name: message_ts
        description: A messages `ts` value, uniquely identifying it within a channel
      - in: query
        name: token
        description: Authentication token
      responses:
        200:
          description: OK
      tags:
      - Messages
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---