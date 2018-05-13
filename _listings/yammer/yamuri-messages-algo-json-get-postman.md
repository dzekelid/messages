{
  "info": {
    "name": "Yammer API GET Algo Messages",
    "_postman_id": "62655758-d64f-4106-b8dd-523d59a7e62b",
    "description": "The algorithmic feed for the user that corresponds to “Top” conversations, which is what the vast majority of users will see in the Yammer web interface.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "da3a50eb-27b2-4c92-9808-fbc7302e5a3f",
          "name": "GET 'Algo' Messages_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages/algo.json"
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
            "description": "The algorithmic feed for the user that corresponds to “Top” conversations, which is what the vast majority of users will see in the Yammer web interface"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6d985c1-a4ae-47fe-9f62-b689d414c303"
            }
          ]
        }
      ]
    }
  ]
}