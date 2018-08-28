---
swagger: "2.0"
x-collection-name: ChainGenie
x-complete: 0
info:
  title: ChainGenie Write message to blockchain
  description: Post string hash into eth chain for POE (proof of existence)
  version: "1.0"
host: api.chaingenie.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ethledger/existsstr:
    post:
      summary: Check message exists on blockchain
      description: Check if your string exists in the eth blockchain
      operationId: EthledgerExistsstrPost
      x-api-path-slug: ethledgerexistsstr-post
      parameters:
      - in: header
        name: ApiKey
      - in: formData
        name: str
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Check
      - Message
      - Exists
      - "On"
      - Blockchain
  /ethledger/poststr:
    post:
      summary: Write message to blockchain
      description: Post string hash into eth chain for POE (proof of existence)
      operationId: EthledgerPoststrPost
      x-api-path-slug: ethledgerpoststr-post
      parameters:
      - in: header
        name: ApiKey
      - in: formData
        name: str
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Write
      - Message
      - To
      - Blockchain
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