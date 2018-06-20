---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
---