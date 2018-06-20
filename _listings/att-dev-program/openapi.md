---
swagger: "2.0"
x-collection-name: AT&T Dev Program
x-complete: 1
info:
  title: AT&T API
  description: this-is-a-complete-definition-of-the-att-api--needs-to-be-broken-into-separate-endpoints-
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
  /myMessages/v2/delta:
    get:
      summary: Get My Delta
      description: /myMessages/v2/delta
      operationId: mymessagesv2delta
      x-api-path-slug: mymessagesv2delta-get
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VDelta
  /myMessages/v2/messages:
    delete:
      summary: Delete My Messages
      description: /myMessages/v2/messages
      operationId: mymessagesv2messages
      x-api-path-slug: mymessagesv2messages-delete
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
    get:
      summary: Get My Messages
      description: /myMessages/v2/messages
      operationId: mymessagesv2messages
      x-api-path-slug: mymessagesv2messages-get
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
    post:
      summary: Post My Messages
      description: /myMessages/v2/messages
      operationId: mymessagesv2messages
      x-api-path-slug: mymessagesv2messages-post
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
  /myMessages/v2/messages/index:
    post:
      summary: Post My Messages Index
      description: /myMessages/v2/messages/index
      operationId: mymessagesv2messagesindex
      x-api-path-slug: mymessagesv2messagesindex-post
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
      - Index
  /myMessages/v2/messages/index/info:
    get:
      summary: Get My Messages Index Info
      description: /myMessages/v2/messages/index/info
      operationId: mymessagesv2messagesindexinfo
      x-api-path-slug: mymessagesv2messagesindexinfo-get
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
      - Index
      - Info
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
  /myMessages/v2/notificationConnectionDetails:
    get:
      summary: Get My Notificationconnectiondetails
      description: /myMessages/v2/notificationConnectionDetails
      operationId: mymessagesv2notificationconnectiondetails
      x-api-path-slug: mymessagesv2notificationconnectiondetails-get
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VNotificationConnectionDetails
---