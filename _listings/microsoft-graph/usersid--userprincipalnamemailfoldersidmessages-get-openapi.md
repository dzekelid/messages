---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph List Messages
  description: List messages Get all the messages in the signed-in user's mailbox,
    or those messages in a specified folder in the mailbox.
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