---
swagger: "2.0"
x-collection-name: Cisco WebEx
x-complete: 0
info:
  title: WebEx Teams API List messages
  description: "Lists all messages in a room. If present, includes the associated
    media content attachment for each message.\r\n\r\nThe list sorts the messages
    in descending order by creation date.\r\n\r\nhttps://developer.webex.com/endpoint-messages-get.html"
  version: 1.0.0
host: api.ciscospark.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /events:
    get:
      summary: List Events (new messages)
      description: |-
        List events in your organization. Several query parameters are available to filter the response.
        Long result sets will be split into pages.

        https://developer.webex.com/endpoint-events-get.html
      operationId: EventsGet4
      x-api-path-slug: events-get
      parameters:
      - in: query
        name: resource
      - in: query
        name: type
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - List
      - Events
      - (new
      - Messages)
  /messages:
    get:
      summary: List messages
      description: "Lists all messages in a room. If present, includes the associated
        media content attachment for each message.\r\n\r\nThe list sorts the messages
        in descending order by creation date.\r\n\r\nhttps://developer.webex.com/endpoint-messages-get.html"
      operationId: MessagesGet
      x-api-path-slug: messages-get
      parameters:
      - in: query
        name: roomId
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
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