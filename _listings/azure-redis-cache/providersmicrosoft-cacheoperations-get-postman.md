{
  "info": {
    "name": "Azure Redis Cache API Operations List",
    "_postman_id": "eeb88064-511e-4ba4-9bc2-aa7a42b3076d",
    "description": "Lists all of the available REST API operations of the Microsoft.Cache provider.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "operations",
      "item": [
        {
          "id": "d900883a-8289-40da-b86f-383b2f167b29",
          "name": "Operations_List",
          "request": {
            "url": "http://management.azure.com/providers/Microsoft.Cache/operations?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the available REST API operations of the Microsoft"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ee7dbdc-ff79-4073-809f-da45c29b9f11"
            }
          ]
        }
      ]
    }
  ]
}