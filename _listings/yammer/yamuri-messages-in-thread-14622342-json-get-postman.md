{
  "info": {
    "name": "Yammer API Get In Thread Messages",
    "_postman_id": "5bbec50f-1f27-4f88-8d4d-2b2c8776fc8e",
    "description": "Get In Thread Messages",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "780da70f-3fbc-4690-bf10-e9c4e1caebf4",
          "name": "Get_In Thread Messages_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages/in_thread/14622342.json"
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
            "description": "Get In Thread Messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1074a732-c7e9-4b9d-9cd8-c294d6e92cd0"
            }
          ]
        }
      ]
    }
  ]
}