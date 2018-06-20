---
swagger: "2.0"
x-collection-name: Kubernetes
x-complete: 0
info:
  title: Kubernetes Delete Namespaces Services Name
  version: 1.0.0
  description: Delete a service.
host: /api/v1beta3
basePath: 127.0.0.1:6443
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1beta3/namespaces/{namespaces}/services:
    get:
      summary: Get Namespaces Services
      description: List objects of kind service.
      operationId: listService
      x-api-path-slug: apiv1beta3namespacesnamespacesservices-get
      parameters:
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Services
    post:
      summary: Post Namespaces Services
      description: Create a service.
      operationId: createService
      x-api-path-slug: apiv1beta3namespacesnamespacesservices-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Services
  /api/v1beta3/namespaces/{namespaces}/services/{name}:
    delete:
      summary: Delete Namespaces Services Name
      description: Delete a service.
      operationId: deleteService
      x-api-path-slug: apiv1beta3namespacesnamespacesservicesname-delete
      parameters:
      - in: path
        name: name
        description: name of the Service
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Services
      - Name
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