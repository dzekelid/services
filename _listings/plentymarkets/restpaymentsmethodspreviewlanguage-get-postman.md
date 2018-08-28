{
  "info": {
    "name": "Plentymarkets Get a preview list for parcel services.",
    "_postman_id": "93e3227c-e94c-4086-b14b-f689145aad58",
    "description": "Get a preview list for parcel services..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Preview",
      "item": [
        {
          "id": "e5261b20-305d-4b44-8568-ee07ab302cb8",
          "name": "getRestListingsOptionTemplatesPreview",
          "request": {
            "url": "http://example.com/rest/listings/option_templates/preview",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a preview list of all available listing option templates."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60d0c524-c7e5-4bc9-acf1-fa98a8045cf0"
            }
          ]
        },
        {
          "id": "0b342824-4583-4539-b7b5-d43e2c516597",
          "name": "getRestOrdersShippingParcelsPreviewLanguage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/orders/shipping/parcels/preview/:language?"
              ],
              "query": [
                {
                  "key": "language",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "language?",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a preview list for parcel services.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "abf4d058-4737-407a-be37-07ec52e45de6"
            }
          ]
        },
        {
          "id": "c6c7d964-e4cc-4bd8-bac6-b7b54f3b243d",
          "name": "getRestOrdersShippingPresetsPreviewLanguage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/orders/shipping/presets/preview/:language?"
              ],
              "query": [
                {
                  "key": "language",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "language?",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a preview list for parcel service presets.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "39f48578-ee2d-41d7-aa6f-cd09d613a795"
            }
          ]
        },
        {
          "id": "6bceac5b-f242-48b8-9401-38152bc216b5",
          "name": "getRestPaymentsMethodsPreviewLanguage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/payments/methods/preview/:language?"
              ],
              "query": [
                {
                  "key": "language",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "language?",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a preview list for parcel services.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03f9b462-5d37-4229-8ab3-24cf3d84c9d6"
            }
          ]
        }
      ]
    }
  ]
}