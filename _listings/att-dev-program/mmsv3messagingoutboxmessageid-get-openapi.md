---
swagger: "2.0"
x-collection-name: AT&T Dev Program
x-complete: 0
info:
  title: AT&T API Get Mms Messaging Outbox Messageid
  description: /mms/v3/messaging/outbox/{messageId}
  version: "1"
host: api.att.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3/smsmessaging/inbound/registrations/{registrationId}/messages:
    get:
      summary: Get SMS Inbound Registrations Registrationid Messages
      description: /3/smsmessaging/inbound/registrations/{registrationId}/messages
      operationId: 3smsmessaginginboundregistrationsregistrationidmessages
      x-api-path-slug: 3smsmessaginginboundregistrationsregistrationidmessages-get
      parameters:
      - in: path
        name: registrationId
      responses:
        200:
          description: OK
      tags:
      - Smsmessaging
      - Inbound
      - Registrations
      - RegistrationId
      - Messages
  /mms/v3/messaging/outbox/{messageId}:
    get:
      summary: Get Mms Messaging Outbox Messageid
      description: /mms/v3/messaging/outbox/{messageId}
      operationId: mmsv3messagingoutboxmessageid
      x-api-path-slug: mmsv3messagingoutboxmessageid-get
      parameters:
      - in: path
        name: messageId
      responses:
        200:
          description: OK
      tags:
      - Mms
      - VMessaging
      - Outbox
      - MessageId
  /myMessages/v2/messages/{messageId}:
    delete:
      summary: Delete My Messages Messageid
      description: /myMessages/v2/messages/{messageId}
      operationId: mymessagesv2messagesmessageid
      x-api-path-slug: mymessagesv2messagesmessageid-delete
      parameters:
      - in: path
        name: messageId
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
      - MessageId
    get:
      summary: Get My Messages Messageid
      description: /myMessages/v2/messages/{messageId}
      operationId: mymessagesv2messagesmessageid
      x-api-path-slug: mymessagesv2messagesmessageid-get
      parameters:
      - in: path
        name: messageId
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
      - MessageId
  /myMessages/v2/messages/{messageId}/parts/{partId}:
    get:
      summary: Get My Messages Messageid Parts Partid
      description: /myMessages/v2/messages/{messageId}/parts/{partId}
      operationId: mymessagesv2messagesmessageidpartspartid
      x-api-path-slug: mymessagesv2messagesmessageidpartspartid-get
      parameters:
      - in: path
        name: messageId
      - in: path
        name: partId
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
      - MessageId
      - Parts
      - PartId
  /sms/v3/messaging/outbox/{messageId}:
    get:
      summary: Get SMS Messaging Outbox Messageid
      description: /sms/v3/messaging/outbox/{messageId}
      operationId: smsv3messagingoutboxmessageid
      x-api-path-slug: smsv3messagingoutboxmessageid-get
      parameters:
      - in: path
        name: messageId
      responses:
        200:
          description: OK
      tags:
      - Sms
      - VMessaging
      - Outbox
      - MessageId
  /3/messaging/outbound/{senderAddress}/requests:
    post:
      summary: Post Messaging Outbound Senderaddress Requests
      description: /3/messaging/outbound/{senderAddress}/requests
      operationId: 3messagingoutboundsenderaddressrequests
      x-api-path-slug: 3messagingoutboundsenderaddressrequests-post
      parameters:
      - in: path
        name: senderAddress
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Outbound
      - Senderress
      - Requests
  /3/messaging/outbound/{senderAddress}/{requestId}/deliveryInfos:
    get:
      summary: Get Messaging Outbound Senderaddress Requestid Deliveryinfos
      description: /3/messaging/outbound/{senderAddress}/{requestId}/deliveryInfos
      operationId: 3messagingoutboundsenderaddressrequestiddeliveryinfos
      x-api-path-slug: 3messagingoutboundsenderaddressrequestiddeliveryinfos-get
      parameters:
      - in: path
        name: requestId
      - in: path
        name: senderAddress
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Outbound
      - Senderress
      - RequestId
      - DeliveryInfos
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