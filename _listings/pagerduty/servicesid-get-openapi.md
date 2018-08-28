---
swagger: "2.0"
x-collection-name: PagerDuty
x-complete: 0
info:
  title: PagerDuty Get a service
  version: 1.0.0
  description: Get details about an existing service.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /services:
    get:
      summary: List services
      description: List existing services.
      operationId: list-existing-services
      x-api-path-slug: services-get
      parameters:
      - in: query
        name: include[]
        description: Array of additional details to include
      - in: query
        name: No Name
      - in: query
        name: query
        description: Filters the result, showing only the services whose name or service_key
          matches the query
      responses:
        200:
          description: OK
      tags:
      - Services
    post:
      summary: Create a service
      description: Create a new service.
      operationId: create-a-new-service
      x-api-path-slug: services-post
      parameters:
      - in: body
        name: service
        description: The service to be created
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Services
  /services/{id}:
    get:
      summary: Get a service
      description: Get details about an existing service.
      operationId: get-details-about-an-existing-service
      x-api-path-slug: servicesid-get
      parameters:
      - in: query
        name: include[]
        description: Array of additional details to include
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