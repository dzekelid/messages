{
  "info": {
    "name": "Yammer API GetPrivate Messages",
    "_postman_id": "8bf71db9-5095-45b8-9ca5-880623056423",
    "description": "Private messages received by the user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "65ade65d-0595-4f3e-96d8-86f25c019087",
          "name": "Get_'Private' Messages_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages/private.json"
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
            "description": "Private messages received by the user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5dafe21c-6c89-4011-8a99-f490c412719a"
            }
          ]
        }
      ]
    }
  ]
}