swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/orders/shipping/parcels/preview/{language?}:
    get:
      summary: Get a preview list for parcel services.
      description: Get a preview list for parcel services..
      operationId: getRestOrdersShippingParcelsPreviewLanguage
      x-api-path-slug: restordersshippingparcelspreviewlanguage-get
      parameters:
      - in: query
        name: language
      - in: path
        name: language?
      responses:
        200:
          description: OK
      tags:
      - Preview
      - Listparcel
      - Services
  /rest/payments/methods/preview/{language?}:
    get:
      summary: Get a preview list for parcel services.
      description: Get a preview list for parcel services..
      operationId: getRestPaymentsMethodsPreviewLanguage
      x-api-path-slug: restpaymentsmethodspreviewlanguage-get
      parameters:
      - in: query
        name: language
      - in: path
        name: language?
      responses:
        200:
          description: OK
      tags:
      - Preview
      - Listparcel
      - Services