swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /my/conversations/{conversation_id}/messages:
    post:
      summary: Post My Conversations Conversation Messages
      description: Post my conversations conversation messages.
      operationId: postMyConversationsConversationMessages
      x-api-path-slug: myconversationsconversation-idmessages-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: conversation_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Conversations
      - Conversation
      - Id
      - Messages