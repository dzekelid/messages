swagger: "2.0"
x-collection-name: Runscope
x-complete: 1
info:
  title: Runscope
  description: manage-runscope-programmatically-
  version: 1.0.0
host: api.runscope.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /buckets/{bucketKey}/messages:
    delete:
      summary: Delete Buckets Messages
      description: Clear a bucket (remove all messages).
      operationId: buckets.bucketKey.messages.delete
      x-api-path-slug: bucketsbucketkeymessages-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Messages
    get:
      summary: Get Buckets Messages
      description: Retrieve a list of messages in a bucket
      operationId: buckets.bucketKey.messages.get
      x-api-path-slug: bucketsbucketkeymessages-get
      parameters:
      - in: query
        name: before
        description: Only return messages before the given Unix timestamp
      - in: query
        name: count
        description: Maxiumum number of messages to return
      - in: query
        name: No Name
      - in: query
        name: since
        description: Only return messages after the given Unix timestamp
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Messages
    post:
      summary: Add Buckets Messages
      description: Create a message
      operationId: buckets.bucketKey.messages.post
      x-api-path-slug: bucketsbucketkeymessages-post
      parameters:
      - in: body
        name: NewMessage
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Messages
  /buckets/{bucketKey}/messages/{messageId}:
    get:
      summary: Get Buckets Messages Message
      description: Retrieve the details for a single message.
      operationId: buckets.bucketKey.messages.messageId.get
      x-api-path-slug: bucketsbucketkeymessagesmessageid-get
      parameters:
      - in: path
        name: messageId
        description: The unique identifier for this message
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Messages
      - Message