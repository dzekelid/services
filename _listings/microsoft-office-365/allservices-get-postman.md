{
  "info": {
    "name": "Microsoft Office 365 Get All Services",
    "_postman_id": "cbab0cdc-2971-4bcf-bab6-125ae1ef0811",
    "description": "Get all services.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "allservices",
      "item": [
        {
          "id": "b0e947f8-36ce-47a1-aa36-f47729a98b4f",
          "name": "getAllservices",
          "request": {
            "url": "http://outlook.office365.com/ews/odata/Me/AllServices",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get all services"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "739493e6-0f9b-4356-9f33-ef4e7bdd8fd8"
            }
          ]
        }
      ]
    }
  ]
}