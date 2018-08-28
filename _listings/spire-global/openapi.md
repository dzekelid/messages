swagger: "2.0"
x-collection-name: Spire Global
x-complete: 1
info:
  title: Spire API
  description: todo-add-description
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