{
  "info": {
    "name": "Yammer API Get Messages Liked By Current User",
    "_postman_id": "61593299-e928-4eb4-9720-c0ba935789fc",
    "description": "Get Messages Liked By Current User",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages likedcurrent user",
      "item": [
        {
          "id": "07d5dfb8-7d05-4fc4-a08a-1e8c805a4dee",
          "name": "Get_Messages Liked by Current User_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages/liked_by.json"
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
            "description": "Get Messages Liked By Current User"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "924ff205-c57c-4c84-9a4a-da6d7fc28550"
            }
          ]
        }
      ]
    }
  ]
}