{
  "info": {
    "name": "Yammer API GetSpecific Message",
    "_postman_id": "4a3e13a5-a5ad-41d6-9777-a21788e2320f",
    "description": "Returns a specfic message using the messageID key in the environment keys",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "04ff4c06-22f2-41be-a0e5-bdb610ac1768",
          "name": "Get_'Specific Message'_",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a specfic message using the messageID key in the environment keys"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c83331c3-09a9-472e-92cb-5e018fc1224d"
            }
          ]
        }
      ]
    }
  ]
}