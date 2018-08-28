{
  "info": {
    "name": "Yammer API Get Messages In A Specific Group",
    "_postman_id": "2fa673af-9756-4e63-b492-3ab2ca561185",
    "description": "Get Messages In A Specific Group",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "86e6e692-95d8-4e2b-8766-f4ea49cf43b7",
          "name": "Get_Messages in a Specific Group_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/messages/in_group/9651.json"
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
            "description": "Get Messages In A Specific Group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30ec4b5c-db3c-440d-80c8-8c81b015e22f"
            }
          ]
        }
      ]
    }
  ]
}