---
swagger: "2.0"
x-collection-name: Spire Global
x-complete: 0
info:
  title: Spire All Messages from Date/Time Window
  description: |-
    Returns all messages with a timestamp greater than `received_after` and timestamp less than `received_before`.
    Query can also be used without the `received_before` parameter.
    Timestamp must be within the past 7 days.
  version: 1.0.0
host: ais.spire.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /messages:
    get:
      summary: All Messages from Date/Time Window
      description: |-
        Returns all messages with a timestamp greater than `received_after` and timestamp less than `received_before`.
        Query can also be used without the `received_before` parameter.
        Timestamp must be within the past 7 days.
      operationId: MessagesGet4
      x-api-path-slug: messages-get
      parameters:
      - in: query
        name: fields
      - in: query
        name: limit
      - in: query
        name: received_after
      - in: query
        name: received_before
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