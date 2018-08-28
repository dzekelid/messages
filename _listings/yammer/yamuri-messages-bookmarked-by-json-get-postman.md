{
  "info": {
    "name": "Yammer API Get Messages Bookmarked",
    "_postman_id": "8b4d3c73-c770-4715-95e7-6090a42cce20",
    "description": "Get messages bookmarked by ser",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "c61d9e89-0de0-4ccb-badf-b1ddf439e3dc",
          "name": "Get_Messages Bookmarked by Current User_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages/bookmarked_by.json"
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
            "description": "Get messages bookmarked by ser"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7308d62c-4b40-4776-bdfe-2dffd818dfa0"
            }
          ]
        }
      ]
    }
  ]
}