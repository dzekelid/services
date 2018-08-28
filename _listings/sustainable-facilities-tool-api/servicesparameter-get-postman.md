{
  "info": {
    "name": "Sustainable Facilities Tool API Services",
    "_postman_id": "43d1c311-3a20-4f15-9717-1001c2aba738",
    "description": "Returns a service by parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "services",
      "item": [
        {
          "id": "1a7dc552-9472-4980-8a4c-8428bc6eac1c",
          "name": "getService",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "services/:parameter"
              ],
              "variable": [
                {
                  "id": "parameter",
                  "value": "parameter",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a service by parameter"
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
              "id": "c30599cc-50c7-4499-9401-98ef089c3cad"
            }
          ]
        }
      ]
    }
  ]
}