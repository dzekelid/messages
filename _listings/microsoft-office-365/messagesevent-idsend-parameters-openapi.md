---
swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 0
info:
  title: Microsoft Office 365 Parameters Messages Event Send
  description: Parameters messages event  send
  version: 1.0.0
host: outlook.office365.com
basePath: /ews/odata/Me
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Folders{folder_id}/Messages:
    get:
      summary: Get Folders Folder Messages
      description: You can request all the emails and meeting requests in a fol...
      operationId: getFoldersFolderMessages
      x-api-path-slug: foldersfolder-idmessages-get
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
      - ""
      - Messages
    post:
      summary: Add Folders Folder Messages
      description: You can create an email by sending a POST request with a JSO...
      operationId: postFoldersFolderMessages
      x-api-path-slug: foldersfolder-idmessages-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: MessageDisposition
        description: When sending a POST request to create an email, there is an optional
          MessageDisposition query parameter that controls what happens to the message
          as it is created
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
      - ""
      - Messages
    parameters:
      summary: Parameters Folders Folder Messages
      description: Parameters folders folder  messages
      operationId: parametersFoldersFolderMessages
      x-api-path-slug: foldersfolder-idmessages-parameters
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
      - ""
      - Messages
  /Messages{event_id}/Send:
    post:
      summary: Add Messages Event Send
      description: You can send an existing email that has the IsDraft property...
      operationId: postMessagesEventSend
      x-api-path-slug: messagesevent-idsend-post
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Event
      - ""
      - Send
    parameters:
      summary: Parameters Messages Event Send
      description: Parameters messages event  send
      operationId: parametersMessagesEventSend
      x-api-path-slug: messagesevent-idsend-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Event
      - ""
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