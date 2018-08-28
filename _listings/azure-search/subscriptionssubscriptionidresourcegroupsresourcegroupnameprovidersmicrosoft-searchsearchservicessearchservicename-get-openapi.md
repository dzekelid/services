---
swagger: "2.0"
x-collection-name: Azure Search
x-complete: 0
info:
  title: Azure Search API Services Get
  description: Gets the Search service with the given name in the given resource group.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Search/searchServices/{searchServiceName}:
    put:
      summary: Services Create Or Update
      description: Creates or updates a Search service in the given resource group.
        If the Search service already exists, all properties will be updated with
        the given values.
      operationId: Services_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-put
      parameters:
      - in: query
        name: No Name
      - in: path
        name: searchServiceName
        description: The name of the Azure Search service to create or update
      - in: body
        name: service
        description: The definition of the Search service to create or update
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Services
    get:
      summary: Services Get
      description: Gets the Search service with the given name in the given resource
        group.
      operationId: Services_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Services
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---