{
  "info": {
    "name": "Yammer API DeleteSpecific Message",
    "_postman_id": "02ed71c0-b9a6-4a4c-af52-4fe5f88c7468",
    "description": "Remove a message. The message must be owned by the current user\n\nDELETE requests should use querystring parameters. If your app does not support the DELETE method you can do a POST with the parameter _method=DELETE.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "09a38ee1-f5a1-4dca-bbbe-b07fd002c7c5",
          "name": "Delete_'Specific Message'_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages/:message_id.json"
              ],
              "variable": [
                {
                  "id": "message_id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "yamURI",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a message"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d95d165e-cd73-4004-8287-13ee624fd837"
            }
          ]
        }
      ]
    }
  ]
}