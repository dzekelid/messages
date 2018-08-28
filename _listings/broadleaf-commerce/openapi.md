swagger: "2.0"
x-collection-name: Broadleaf Commerce
x-complete: 1
info:
  title: Broadleaf Commerce API
  description: the-default-broadleaf-commerce-apis
  version: 1.0.0
host: demo.broadleafcommerce.org
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /promotion-messages/{productId}:
    get:
      summary: Get Promotion Messages
      description: Get promotion messages.
      operationId: getPromotionMessagesProduct
      x-api-path-slug: promotionmessagesproductid-get
      parameters:
      - in: path
        name: productId
        description: productId
      responses:
        200:
          description: OK
      tags:
      - Promotion
      - Messages