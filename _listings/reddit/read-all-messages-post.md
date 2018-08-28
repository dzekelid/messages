---
swagger: "2.0"
info:
  title: Reddit Add Read All Messages
  description: Queue up marking all messages for a user as read.
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /read_all_messages:
    post:
      summary: Add Read All Messages
      description: Queue up marking all messages for a user as read
      operationId: post&nbsp;ReadAllMessages
      parameters:
      - in: query
        name: filter_types
        description: A comma-separated list of items
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - read
      - messages
definitions: []
x-collection-name: Reddit
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