{
  "info": {
    "name": "Yammer API GET Following Messages",
    "_postman_id": "47b4683b-a0ce-4a0d-a131-7ec2a8ab9ab3",
    "description": "The “Following” feed which is conversations involving people, groups and topics that the user is following.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "4d6014f2-0bc9-4b29-b75e-b3a710b91a86",
          "name": "GET 'Following' Messages_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages/following.json"
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
            "description": "The “Following” feed which is conversations involving people, groups and topics that the user is following"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00ef7f6a-ea14-4d29-ad58-709c6d73b9c7"
            }
          ]
        }
      ]
    }
  ]
}