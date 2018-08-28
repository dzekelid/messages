---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Get Message
  description: Get message Retrieve the properties and relationships of a message
    object.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/mailFolders/{id}/messages:
    get:
      summary: List Messages
      description: List messages Get all the messages in the signed-in user's mailbox,
        or those messages in a specified folder in the mailbox.
      operationId: ListMessages
      x-api-path-slug: memailfoldersidmessages-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Messages
    post:
      summary: Create Message
      description: Create Message Use this API to create a new Message in a mailfolder.
      operationId: CreateMessage
      x-api-path-slug: memailfoldersidmessages-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
  /users/{id | userPrincipalName}/mailFolders/{id}/messages:
    get:
      summary: List Messages
      description: List messages Get all the messages in the signed-in user's mailbox,
        or those messages in a specified folder in the mailbox.
      operationId: ListMessages
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessages-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Messages
    post:
      summary: Create Message
      description: Create Message Use this API to create a new Message in a mailfolder.
      operationId: CreateMessage
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessages-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
  /users/{id | userPrincipalName}/messages:
    get:
      summary: List Messages
      description: List messages Get the messages in the signed-in user's mailbox
        (including the Deleted Items and Clutter folders).
      operationId: ListMessages
      x-api-path-slug: usersid--userprincipalnamemessages-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Messages
  /me/messages/{id}:
    delete:
      summary: Delete Message
      description: Delete message Delete message.
      operationId: DeleteMessage
      x-api-path-slug: memessagesid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
    get:
      summary: Get Message
      description: Get message Retrieve the properties and relationships of a message
        object.
      operationId: GetMessage
      x-api-path-slug: memessagesid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
    patch:
      summary: Update Message
      description: Update message Update the properties of message object.
      operationId: UpdateMessage
      x-api-path-slug: memessagesid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
  /users/{id | userPrincipalName}/messages/{id}:
    delete:
      summary: Delete Message
      description: Delete message Delete message.
      operationId: DeleteMessage
      x-api-path-slug: usersid--userprincipalnamemessagesid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
    get:
      summary: Get Message
      description: Get message Retrieve the properties and relationships of a message
        object.
      operationId: GetMessage
      x-api-path-slug: usersid--userprincipalnamemessagesid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
    patch:
      summary: Update Message
      description: Update message Update the properties of message object.
      operationId: UpdateMessage
      x-api-path-slug: usersid--userprincipalnamemessagesid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
  /me/mailFolders/{id}/messages/{id}:
    delete:
      summary: Delete Message
      description: Delete message Delete message.
      operationId: DeleteMessage
      x-api-path-slug: memailfoldersidmessagesid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
    get:
      summary: Get Message
      description: Get message Retrieve the properties and relationships of a message
        object.
      operationId: GetMessage
      x-api-path-slug: memailfoldersidmessagesid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
    patch:
      summary: Update Message
      description: Update message Update the properties of message object.
      operationId: UpdateMessage
      x-api-path-slug: memailfoldersidmessagesid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}:
    delete:
      summary: Delete Message
      description: Delete message Delete message.
      operationId: DeleteMessage
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
    get:
      summary: Get Message
      description: Get message Retrieve the properties and relationships of a message
        object.
      operationId: GetMessage
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
    patch:
      summary: Update Message
      description: Update message Update the properties of message object.
      operationId: UpdateMessage
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesid-patch
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
  /me/messages/{id}/copy:
    post:
      summary: Message Copy
      description: 'message: copy Copy a message to a folder.'
      operationId: Message:Copy
      x-api-path-slug: memessagesidcopy-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Copy
  /users/{id | userPrincipalName}/messages/{id}/copy:
    post:
      summary: Message Copy
      description: 'message: copy Copy a message to a folder.'
      operationId: Message:Copy
      x-api-path-slug: usersid--userprincipalnamemessagesidcopy-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Copy
  /me/mailFolders/{id}/messages/{id}/copy:
    post:
      summary: Message Copy
      description: 'message: copy Copy a message to a folder.'
      operationId: Message:Copy
      x-api-path-slug: memailfoldersidmessagesidcopy-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Copy
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/copy:
    post:
      summary: Message Copy
      description: 'message: copy Copy a message to a folder.'
      operationId: Message:Copy
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidcopy-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Copy
  /me/messages/{id}/createForward:
    post:
      summary: Message Create Forward
      description: 'message: createForward Create a draft of the Forward message.
        You can then update or send the draft.'
      operationId: Message:CreateForward
      x-api-path-slug: memessagesidcreateforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /users/{id | userPrincipalName}/messages/{id}/createForward:
    post:
      summary: Message Create Forward
      description: 'message: createForward Create a draft of the Forward message.
        You can then update or send the draft.'
      operationId: Message:CreateForward
      x-api-path-slug: usersid--userprincipalnamemessagesidcreateforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /me/mailFolders/{id}/messages/{id}/createForward:
    post:
      summary: Message Create Forward
      description: 'message: createForward Create a draft of the Forward message.
        You can then update or send the draft.'
      operationId: Message:CreateForward
      x-api-path-slug: memailfoldersidmessagesidcreateforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createForward:
    post:
      summary: Message Create Forward
      description: 'message: createForward Create a draft of the Forward message.
        You can then update or send the draft.'
      operationId: Message:CreateForward
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /me/messages/{id}/createReply:
    post:
      summary: Message Create Reply
      description: 'message: createReply Create a draft of the Reply message. You
        can then update or send the draft.'
      operationId: Message:CreateReply
      x-api-path-slug: memessagesidcreatereply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/messages/{id}/createReply:
    post:
      summary: Message Create Reply
      description: 'message: createReply Create a draft of the Reply message. You
        can then update or send the draft.'
      operationId: Message:CreateReply
      x-api-path-slug: usersid--userprincipalnamemessagesidcreatereply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/mailFolders/{id}/messages/{id}/createReply:
    post:
      summary: Message Create Reply
      description: 'message: createReply Create a draft of the Reply message. You
        can then update or send the draft.'
      operationId: Message:CreateReply
      x-api-path-slug: memailfoldersidmessagesidcreatereply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createReply:
    post:
      summary: Message Create Reply
      description: 'message: createReply Create a draft of the Reply message. You
        can then update or send the draft.'
      operationId: Message:CreateReply
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/messages/{id}/createReplyAll:
    post:
      summary: Message Create Reply All
      description: 'message: createReplyAll Create a draft of the Reply All message.
        You can then update or send the draft.'
      operationId: Message:CreateReplyAll
      x-api-path-slug: memessagesidcreatereplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/messages/{id}/createReplyAll:
    post:
      summary: Message Create Reply All
      description: 'message: createReplyAll Create a draft of the Reply All message.
        You can then update or send the draft.'
      operationId: Message:CreateReplyAll
      x-api-path-slug: usersid--userprincipalnamemessagesidcreatereplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/mailFolders/{id}/messages/{id}/createReplyAll:
    post:
      summary: Message Create Reply All
      description: 'message: createReplyAll Create a draft of the Reply All message.
        You can then update or send the draft.'
      operationId: Message:CreateReplyAll
      x-api-path-slug: memailfoldersidmessagesidcreatereplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createReplyAll:
    post:
      summary: Message Create Reply All
      description: 'message: createReplyAll Create a draft of the Reply All message.
        You can then update or send the draft.'
      operationId: Message:CreateReplyAll
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/messages/{id}/forward:
    post:
      summary: Message Forward
      description: 'message: forward Forward a message. The message is saved in the
        Sent Items folder.'
      operationId: Message:Forward
      x-api-path-slug: memessagesidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /users/{id | userPrincipalName}/messages/{id}/forward:
    post:
      summary: Message Forward
      description: 'message: forward Forward a message. The message is saved in the
        Sent Items folder.'
      operationId: Message:Forward
      x-api-path-slug: usersid--userprincipalnamemessagesidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /me/mailFolders/{id}/messages/{id}/forward:
    post:
      summary: Message Forward
      description: 'message: forward Forward a message. The message is saved in the
        Sent Items folder.'
      operationId: Message:Forward
      x-api-path-slug: memailfoldersidmessagesidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/forward:
    post:
      summary: Message Forward
      description: 'message: forward Forward a message. The message is saved in the
        Sent Items folder.'
      operationId: Message:Forward
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /me/messages/{id}/move:
    post:
      summary: Message Move
      description: 'message: move Move a message to a folder. This creates a new copy
        of the message in the destination folder.'
      operationId: Message:Move
      x-api-path-slug: memessagesidmove-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Move
  /users/{id | userPrincipalName}/messages/{id}/move:
    post:
      summary: Message Move
      description: 'message: move Move a message to a folder. This creates a new copy
        of the message in the destination folder.'
      operationId: Message:Move
      x-api-path-slug: usersid--userprincipalnamemessagesidmove-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Move
  /me/mailFolders/{id}/messages/{id}/move:
    post:
      summary: Message Move
      description: 'message: move Move a message to a folder. This creates a new copy
        of the message in the destination folder.'
      operationId: Message:Move
      x-api-path-slug: memailfoldersidmessagesidmove-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Move
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/move:
    post:
      summary: Message Move
      description: 'message: move Move a message to a folder. This creates a new copy
        of the message in the destination folder.'
      operationId: Message:Move
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidmove-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Move
  /me/messages/{id}/reply:
    post:
      summary: Message Reply
      description: 'message: reply Reply to the sender of a message. The message is
        then saved in the Sent Items folder.'
      operationId: Message:Reply
      x-api-path-slug: memessagesidreply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/messages/{id}/reply:
    post:
      summary: Message Reply
      description: 'message: reply Reply to the sender of a message. The message is
        then saved in the Sent Items folder.'
      operationId: Message:Reply
      x-api-path-slug: usersid--userprincipalnamemessagesidreply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/mailFolders/{id}/messages/{id}/reply:
    post:
      summary: Message Reply
      description: 'message: reply Reply to the sender of a message. The message is
        then saved in the Sent Items folder.'
      operationId: Message:Reply
      x-api-path-slug: memailfoldersidmessagesidreply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/reply:
    post:
      summary: Message Reply
      description: 'message: reply Reply to the sender of a message. The message is
        then saved in the Sent Items folder.'
      operationId: Message:Reply
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidreply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/me/messages/{id}/replyAll:
    post:
      summary: Message Reply All
      description: 'message: replyAll Reply to all recipients of a message. The message
        is then saved in the Sent Items folder.'
      operationId: Message:ReplyAll
      x-api-path-slug: usersmemessagesidreplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/messages/{id}/replyAll:
    post:
      summary: Message Reply All
      description: 'message: replyAll Reply to all recipients of a message. The message
        is then saved in the Sent Items folder.'
      operationId: Message:ReplyAll
      x-api-path-slug: usersid--userprincipalnamemessagesidreplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/mailFolders/{id}/messages/{id}/replyAll:
    post:
      summary: Message Reply All
      description: 'message: replyAll Reply to all recipients of a message. The message
        is then saved in the Sent Items folder.'
      operationId: Message:ReplyAll
      x-api-path-slug: memailfoldersidmessagesidreplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/replyAll:
    post:
      summary: Message Reply All
      description: 'message: replyAll Reply to all recipients of a message. The message
        is then saved in the Sent Items folder.'
      operationId: Message:ReplyAll
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidreplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/messages/{id}/send:
    post:
      summary: Message Send
      description: 'message: send Send a message in the draft folder. The draft message
        can be a new message draft, reply draft, reply-all draft, or a forward draft.
        The message is then saved in the Sent Items folder.'
      operationId: Message:Send
      x-api-path-slug: memessagesidsend-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Send
  /users/{id | userPrincipalName}/messages/{id}/send:
    post:
      summary: Message Send
      description: 'message: send Send a message in the draft folder. The draft message
        can be a new message draft, reply draft, reply-all draft, or a forward draft.
        The message is then saved in the Sent Items folder.'
      operationId: Message:Send
      x-api-path-slug: usersid--userprincipalnamemessagesidsend-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Send
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