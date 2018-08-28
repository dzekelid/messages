{
  "info": {
    "name": "Yammer API GetReceived Messages",
    "_postman_id": "36a594ac-1871-465e-99b1-ef149c06e103",
    "description": "All messages received by the user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "c67ac7a4-a36a-4b8f-82e0-8a0c5dbe7b85",
          "name": "Get_'Received' Messages_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages/received.json"
              ],
              "variable": [
                {
                  "id": "yamURI",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "All messages received by the user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d20a4ed-b378-45e3-add9-1fc881c8c368"
            }
          ]
        }
      ]
    }
  ]
}