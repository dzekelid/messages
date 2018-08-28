{
  "info": {
    "name": "Yammer API GET My Feed Messages",
    "_postman_id": "f0eded08-27a7-4123-bc2b-a97b702a7fa8",
    "description": "The user’s feed, based on the selection they have made between “Following” and “Top” conversations.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "41f7e97b-03d8-4617-b31e-3fa9d255c36f",
          "name": "GET 'My Feed' Messages_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages/my_feed.json"
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
            "description": "The user’s feed, based on the selection they have made between “Following” and “Top” conversations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9bb40192-1db1-442e-b9d9-f768c5148089"
            }
          ]
        }
      ]
    }
  ]
}