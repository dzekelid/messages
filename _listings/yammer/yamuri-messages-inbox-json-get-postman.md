{
  "info": {
    "name": "Yammer API Get Inbox Messages",
    "_postman_id": "3ea093a6-0c1a-4572-aed7-9d9ce5f08bde",
    "description": "Get Inbox Messages",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "c709c18c-982a-415d-949f-3aa256360f29",
          "name": "Get_'Inbox' Messages_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages/inbox.json"
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
            "description": "Get Inbox Messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77c727d9-92d4-4679-8a99-66840109e952"
            }
          ]
        }
      ]
    }
  ]
}