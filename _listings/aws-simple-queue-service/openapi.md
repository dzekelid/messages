---
swagger: "2.0"
x-collection-name: AWS Simple Queue Service
x-complete: 1
info:
  title: AWS Simple Queue Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteMessage:
    get:
      summary: Delete Message
      description: Deletes the specified message from the specified queue.
      operationId: deleteMessage
      x-api-path-slug: actiondeletemessage-get
      parameters:
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue from which messages are deleted
        type: string
      - in: query
        name: ReceiptHandle
        description: The receipt handle associated with the message to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Messages
  /?Action=DeleteMessageBatch:
    get:
      summary: Delete Message Batch
      description: Deletes up to ten messages from the specified queue.
      operationId: deleteMessageBatch
      x-api-path-slug: actiondeletemessagebatch-get
      parameters:
      - in: query
        name: DeleteMessageBatchRequestEntry.N
        description: A list of receipt handles for the messages to be deleted
        type: string
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue from which messages are deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Messages
  /?Action=ReceiveMessage:
    get:
      summary: Receive Message
      description: Retrieves one or more messages (up to 10), from the specified queue.
      operationId: receiveMessage
      x-api-path-slug: actionreceivemessage-get
      parameters:
      - in: query
        name: AttributeName.N
        description: A list of attributes that need to be returned along with each
          message
        type: string
      - in: query
        name: MaxNumberOfMessages
        description: The maximum number of messages to return
        type: string
      - in: query
        name: MessageAttributeName.N
        description: The name of the message attribute, where N is the index
        type: string
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue from which messages are received
        type: string
      - in: query
        name: ReceiveRequestAttemptId
        description: This parameter applies only to FIFO (first-in-first-out) queues
        type: string
      - in: query
        name: VisibilityTimeout
        description: The duration (in seconds) that the received messages are hidden
          from subsequent retrieve requests after being retrieved by a ReceiveMessage
          request
        type: string
      - in: query
        name: WaitTimeSeconds
        description: The duration (in seconds) for which the call waits for a message
          to arrive in the queue before returning
        type: string
      responses:
        200:
          description: OK
      tags:
      - Messages
  /?Action=SendMessage:
    get:
      summary: Send Message
      description: Delivers a message to the specified queue.
      operationId: sendMessage
      x-api-path-slug: actionsendmessage-get
      parameters:
      - in: query
        name: DelaySeconds
        description: The number of seconds to delay a specific message
        type: string
      - in: query
        name: |-
          MessageAttribute
                      , MessageAttribute.N.Name (key), MessageAttribute.N.Value (value)
        description: Each message attribute consists of a Name, Type, and Value
        type: string
      - in: query
        name: MessageBody
        description: The message to send
        type: string
      - in: query
        name: MessageDeduplicationId
        description: This parameter applies only to FIFO (first-in-first-out) queues
        type: string
      - in: query
        name: MessageGroupId
        description: This parameter applies only to FIFO (first-in-first-out) queues
        type: string
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue to which a message is sent
        type: string
      responses:
        200:
          description: OK
      tags:
      - Messages
  /?Action=SendMessageBatch:
    get:
      summary: Send Message Batch
      description: Delivers up to ten messages to the specified queue.
      operationId: sendMessageBatch
      x-api-path-slug: actionsendmessagebatch-get
      parameters:
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue to which batched messages are
          sent
        type: string
      - in: query
        name: SendMessageBatchRequestEntry.N
        description: A list of                      SendMessageBatchRequestEntry                   items
        type: string
      responses:
        200:
          description: OK
      tags:
      - Messages
---