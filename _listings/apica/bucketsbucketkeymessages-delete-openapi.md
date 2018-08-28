---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Messages API Delete Buckets Messages
  version: 1.0.0
  description: Clear a bucket (remove all messages)..
host: api.pingdom.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
basePath: /
paths:
  /buckets/{bucketKey}/messages:
    delete:
      summary: Delete Buckets Messages
      description: Clear a bucket (remove all messages)..
      operationId: deleteBucketsBucketkeyMessages
      x-api-path-slug: bucketsbucketkeymessages-delete
      parameters:
      - in: path
        name: bucketKey
        description: Unique identifier for a bucket
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - BucketKey
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