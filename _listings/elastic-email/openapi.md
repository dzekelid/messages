swagger: "2.0"
x-collection-name: Elastic Email
x-complete: 1
info:
  title: Elastic Email SMTP API
  description: api-for-sending-and-management-email-
  version: v1
host: api.elasticemail.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  mailer/status/{message_id}:
    get:
      summary: Get Status
      description: Get the status of an email message
      operationId: getMailerStatusMessage
      x-api-path-slug: mailerstatusmessage-id-get
      parameters:
      - in: query
        name: api_key
        description: Your API Key
      - in: path
        name: message_id
        description: The ID of the email message
      - in: query
        name: showdelivered
        description: true - This will return all the recipients who succeeded
      - in: query
        name: showdetails
        description: true  - This will return all recipients for each status
      - in: query
        name: showerrors
        description: true - This will return all the recipients who bounced with details
          on why
      - in: query
        name: showfailed
        description: true - This will return all the recipients who bounced
      - in: query
        name: showpending
        description: true - This will return all the recipients still in progress
      - in: query
        name: showstats
        description: Show stats
      - in: query
        name: username
        description: Your user name
      responses:
        200:
          description: OK
      tags:
      - Mailer
      - Status
      - Message
      - Id