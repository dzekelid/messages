---
swagger: "2.0"
x-collection-name: Slack
x-complete: 1
info:
  title: Slack
  description: one-way-to-interact-with-the-slack-platform-is-its-http-rpcbased-web-api-a-collection-of-methods-requiring-oauth-2-0based-user-bot-or-workspace-tokens-blessed-with-related-oauth-scopes-
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
  /chat.postEphemeral:
    post:
      summary: Sent Ephemeral lMessage
      description: Sends an ephemeral message to a user in a channel.
      operationId: chat_postEphemeral
      x-api-path-slug: chat-postephemeral-post
      parameters:
      - in: formData
        name: as_user
        description: Pass true to post the message as the authed bot
      - in: formData
        name: attachments
        description: A JSON-based array of structured attachments, presented as a
          URL-encoded string
      - in: formData
        name: channel
        description: Channel, private group, or IM channel to send message to
      - in: formData
        name: link_names
        description: Find and link channel names and usernames
      - in: formData
        name: parse
        description: Change how messages are treated
      - in: formData
        name: text
        description: Text of the message to send
      - in: header
        name: token
        description: Authentication token
      - in: formData
        name: user
        description: '`id` of the user who will receive the ephemeral message'
      responses:
        200:
          description: OK
      tags:
      - Messages
  /chat.update:
    post:
      summary: Update Message
      description: Updates a message.
      operationId: chat_update
      x-api-path-slug: chat-update-post
      parameters:
      - in: formData
        name: as_user
        description: Pass true to update the message as the authed user
      - in: formData
        name: attachments
        description: A JSON-based array of structured attachments, presented as a
          URL-encoded string
      - in: formData
        name: channel
        description: Channel containing the message to be updated
      - in: formData
        name: link_names
        description: Find and link channel names and usernames
      - in: formData
        name: parse
        description: Change how messages are treated
      - in: formData
        name: text
        description: New text for the message, using the [default formatting rules](/docs/formatting)
      - in: header
        name: token
        description: Authentication token
      - in: formData
        name: ts
        description: Timestamp of the message to be updated
      responses:
        200:
          description: OK
      tags:
      - Messages
  /chat.meMessage:
    post:
      summary: Share Message
      description: Share a me message into a channel.
      operationId: chat_meMessage
      x-api-path-slug: chat-memessage-post
      parameters:
      - in: formData
        name: channel
        description: Channel to send message to
      - in: formData
        name: text
        description: Text of the message to send
      - in: header
        name: token
        description: Authentication token
      responses:
        200:
          description: OK
      tags:
      - Messages
  /chat.postMessage:
    post:
      summary: Send Channel Message
      description: Sends a message to a channel.
      operationId: chat_postMessage
      x-api-path-slug: chat-postmessage-post
      parameters:
      - in: formData
        name: as_user
        description: Pass true to post the message as the authed user, instead of
          as a bot
      - in: formData
        name: attachments
        description: A JSON-based array of structured attachments, presented as a
          URL-encoded string
      - in: formData
        name: channel
        description: Channel, private group, or IM channel to send message to
      - in: formData
        name: icon_emoji
        description: Emoji to use as the icon for this message
      - in: formData
        name: icon_url
        description: URL to an image to use as the icon for this message
      - in: formData
        name: link_names
        description: Find and link channel names and usernames
      - in: formData
        name: parse
        description: Change how messages are treated
      - in: formData
        name: reply_broadcast
        description: Used in conjunction with `thread_ts` and indicates whether reply
          should be made visible to everyone in the channel or conversation
      - in: formData
        name: text
        description: Text of the message to send
      - in: formData
        name: thread_ts
        description: Provide another messages `ts` value to make this message a reply
      - in: header
        name: token
        description: Authentication token
      - in: formData
        name: unfurl_links
        description: Pass true to enable unfurling of primarily text-based content
      - in: formData
        name: unfurl_media
        description: Pass false to disable unfurling of media content
      - in: formData
        name: username
        description: Set your bots user name
      responses:
        200:
          description: OK
      tags:
      - Messages
---