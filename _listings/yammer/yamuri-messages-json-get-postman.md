{
  "info": {
    "name": "Yammer API GET Messages",
    "_postman_id": "889fc221-5bd2-4e4b-8f62-13aa2d681be3",
    "description": "All public messages in the user’s (whose access token is being used to make the API call henceforth referred to as current user) Yammer network. Corresponds to “All” conversations in the Yammer web interface.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "d78b3a74-92f3-4147-9e3f-6f2fd850d81e",
          "name": "GET Messages_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages.json"
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
            "description": "All public messages in the user’s (whose access token is being used to make the API call henceforth referred to as current user) Yammer network"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "374fed10-f4ef-49ac-9fe9-8f70dc078734"
            }
          ]
        }
      ]
    }
  ]
}