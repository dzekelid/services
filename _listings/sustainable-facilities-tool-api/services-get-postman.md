{
  "info": {
    "name": "Sustainable Facilities Tool API Services",
    "_postman_id": "18e04eba-fc3f-4447-8fab-1d0060bd8785",
    "description": "Returns all services",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "services",
      "item": [
        {
          "id": "66786bdf-30cc-439c-8bf8-b57996337164",
          "name": "getServices",
          "request": {
            "url": "http://api.data.gov/sftool/v1/services",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all services"
          },
          "response": [
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "[\r\n  {\r\n    \"id\": \"id\",\r\n    \"name\": \"name\"\r\n  }\r\n]",
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "fe7f75cc-d986-47fe-8bbe-c47a9b03549a"
            }
          ]
        }
      ]
    }
  ]
}