---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Get Message Chats Pagenumber Search
  version: 1.0.0
  description: Get message chats pagenumber search.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/notify/messages:
    get:
      summary: Get Notify Messages
      description: Get notify messages.
      operationId: getApiV1NotifyMessages
      x-api-path-slug: apiv1notifymessages-get
      responses:
        200:
          description: OK
      tags:
      - Notify
      - Messages
  /api/v1/message/new/{withUserId}/{lastMessageId}:
    get:
      summary: Get Message New Withuserid Lastmessageid
      description: Get message new withuserid lastmessageid.
      operationId: getApiV1MessageNewWithuserLastmessage
      x-api-path-slug: apiv1messagenewwithuseridlastmessageid-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: lastMessageId
      - in: path
        name: withUserId
      responses:
        200:
          description: OK
      tags:
      - Message
      - New
      - Withuserid
      - Lastmessageid
  /api/v1/message/chats/{pageNumber}/{search}:
    get:
      summary: Get Message Chats Pagenumber Search
      description: Get message chats pagenumber search.
      operationId: getApiV1MessageChatsPagenumberSearch
      x-api-path-slug: apiv1messagechatspagenumbersearch-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: pageNumber
      - in: path
        name: search
      - in: query
        name: unread
      responses:
        200:
          description: OK
      tags:
      - Message
      - Chats
      - Pagenumber
      - Search
  /api/v1/message/send:
    post:
      summary: Post Message Send
      description: Post message send.
      operationId: postApiV1MessageSend
      x-api-path-slug: apiv1messagesend-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: message
        description: ID
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Message
      - Send
  /api/v1/message/chat/{id}/{from}:
    get:
      summary: Get Message Chat From
      description: Get message chat from.
      operationId: getApiV1MessageChatFrom
      x-api-path-slug: apiv1messagechatidfrom-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: from
        description: "20"
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Message
      - Chat
      - From
  /api/v1/message/count/{userId}:
    get:
      summary: Get Message Count Userid
      description: Get message count userid.
      operationId: getApiV1MessageCountUser
      x-api-path-slug: apiv1messagecountuserid-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Message
      - Count
      - Userid
  /api/v1/message/delete:
    post:
      summary: Post Message Delete
      description: Post message delete.
      operationId: postApiV1MessageDelete
      x-api-path-slug: apiv1messagedelete-post
      parameters:
      - in: header
        name: Authorization
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Message
  /api/v1/message/feedback:
    post:
      summary: Post Message Feedback
      description: Post message feedback.
      operationId: postApiV1MessageFeedback
      x-api-path-slug: apiv1messagefeedback-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Message
      - Feedback
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