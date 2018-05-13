{
  "info": {
    "name": "Yammer API GetSent Messages",
    "_postman_id": "d1f81f9d-d895-42f4-98a6-b05aeb565164",
    "description": "All messages sent by the user. Alias for /api/v1/messages/from_user/logged-in_user_id.format.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "b092620e-34a8-48c6-9e5e-a6d8bb3cc8fd",
          "name": "Get_'Sent' Messages_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages/sent.json"
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
            "description": "All messages sent by the user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6750e118-5dd4-41e5-8769-6c4e08269081"
            }
          ]
        }
      ]
    }
  ]
}