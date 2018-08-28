{
  "info": {
    "name": "GIGANDCROWD Get Message Count Userid",
    "_postman_id": "9ffcfe8a-0f78-4f3a-ae5d-97e6307abb6a",
    "description": "Get message count userid.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Message",
      "item": [
        {
          "id": "cf9fa107-a35b-4219-bf5f-a2dcc5e22697",
          "name": "getApiV1MessageCountUser",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/message/count/:userId"
              ],
              "variable": [
                {
                  "id": "userId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get message count userid."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "879e704d-c1c5-41d9-8268-557811b105cf"
            }
          ]
        }
      ]
    }
  ]
}