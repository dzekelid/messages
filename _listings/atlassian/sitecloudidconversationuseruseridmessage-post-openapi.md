---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Software Cloud API Send message to a user
  description: Send message to a user.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /site/{cloudId}/conversation/user/{userId}/message:
    post:
      summary: Send message to a user
      description: Send message to a user.
      operationId: UserMessagePostHandler
      x-api-path-slug: sitecloudidconversationuseruseridmessage-post
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: userId
        description: The user Id
      responses:
        200:
          description: OK
      tags:
      - Send
      - Message
      - To
      - User
  /site/{cloudId}/conversation/user/{userId}/message/{messageId}:
    put:
      summary: Edit a message in a direct conversation
      description: Authentication required, with scope participate:conversation
      operationId: UserMessagePutHandler
      x-api-path-slug: sitecloudidconversationuseruseridmessagemessageid-put
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: messageId
        description: The ID of the message
      - in: path
        name: userId
        description: The user Id
      responses:
        200:
          description: OK
      tags:
      - Edit
      - Message
      - In
      - Direct
      - Conversation
    delete:
      summary: Delete a message in a direct conversation
      description: Authentication required, with scope participate:conversation
      operationId: UserMessageDeleteHandler
      x-api-path-slug: sitecloudidconversationuseruseridmessagemessageid-delete
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: messageId
        description: The ID of the message
      - in: path
        name: userId
        description: The user Id
      responses:
        200:
          description: OK
      tags:
      - Message
      - In
      - Direct
      - Conversation
  /site/{cloudId}/conversation/{conversationId}/message:
    post:
      summary: Send a message to a conversation
      description: Send a message to a conversation.
      operationId: ConversationMessagePostHandler
      x-api-path-slug: sitecloudidconversationconversationidmessage-post
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      responses:
        200:
          description: OK
      tags:
      - Send
      - Message
      - To
      - Conversation
  /site/{cloudId}/conversation/{conversationId}/message/{messageId}:
    get:
      summary: Get Message by id
      description: Authentication required, with scope participate:conversation
      operationId: ConversationMessageGetHandler
      x-api-path-slug: sitecloudidconversationconversationidmessagemessageid-get
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      - in: path
        name: messageId
        description: The ID of the Message to retrieve
      responses:
        200:
          description: OK
      tags:
      - Message
      - By
      - Id
    put:
      summary: Edit a message in a conversation
      description: Authentication required, with scope participate:conversation
      operationId: ConversationMessagePutHandler
      x-api-path-slug: sitecloudidconversationconversationidmessagemessageid-put
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      - in: path
        name: messageId
        description: The ID of the message
      responses:
        200:
          description: OK
      tags:
      - Edit
      - Message
      - In
      - Conversation
    delete:
      summary: Delete a message in a conversation
      description: Authentication required, with scope participate:conversation
      operationId: ConversationMessageDeleteHandler
      x-api-path-slug: sitecloudidconversationconversationidmessagemessageid-delete
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      - in: path
        name: messageId
        description: The ID of the message
      responses:
        200:
          description: OK
      tags:
      - Message
      - In
      - Conversation
  /site/{cloudId}/conversation/{conversationId}/message/recent:
    get:
      summary: Get latest messages for conversation
      description: Authentication required, with scope participate:conversation Max
        number of messages returned is 75.
      operationId: ConversationMessagesRecentGetHandler
      x-api-path-slug: sitecloudidconversationconversationidmessagerecent-get
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      - in: query
        name: limit
        description: The maximum number of results
      responses:
        200:
          description: OK
      tags:
      - Latest
      - Messagesconversation
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