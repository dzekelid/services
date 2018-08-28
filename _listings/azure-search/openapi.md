swagger: "2.0"
x-collection-name: Azure Search
x-complete: 1
info:
  title: SearchManagementClient
  description: client-that-can-be-used-to-manage-azure-search-services-and-api-keys-
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
    delete:
      summary: Services Delete
      description: Deletes a Search service in the given resource group, along with
        its associated resources.
      operationId: Services_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Services