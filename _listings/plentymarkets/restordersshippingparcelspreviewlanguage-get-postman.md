{
  "info": {
    "name": "Plentymarkets Get a preview list for parcel services.",
    "_postman_id": "6a67d76a-9f9d-4e22-94cd-929f042ece90",
    "description": "Get a preview list for parcel services..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Preview",
      "item": [
        {
          "id": "34742d88-fb73-4861-b3fd-fbbaab6e2130",
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
              "id": "3d8cf431-a738-4f2c-99cb-09b073449eca"
            }
          ]
        },
        {
          "id": "1b1ccac2-f565-4344-a409-bc06263235ac",
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
              "id": "544360b2-c75b-4000-a854-d2f09840f63c"
            }
          ]
        }
      ]
    }
  ]
}