swagger: "2.0"
x-collection-name: Vinli
x-complete: 1
info:
  title: Vinli
  description: todo-add-description
  version: 1.0.0
host: events.vin.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /devices/cf217c2d-df3c-41f7-b610-8bc3e11b4b79/messages:
    get:
      summary: List Telemetry Messages
      description: List telemetry messages.
      operationId: DevicesCf217c2dDf3c41f7B6108bc3e11b4b79MessagesGet
      x-api-path-slug: devicescf217c2ddf3c41f7b6108bc3e11b4b79messages-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - Telemetry
      - Messages
  /messages/ade8e85c-a1aa-4373-8c6e-e37e87762f29:
    get:
      summary: Get a Specific Telemety Message
      description: Get a specific telemety message.
      operationId: MessagesAde8e85cA1aa43738c6eE37e87762f29Get
      x-api-path-slug: messagesade8e85ca1aa43738c6ee37e87762f29-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Specific
      - Telemety
      - Message