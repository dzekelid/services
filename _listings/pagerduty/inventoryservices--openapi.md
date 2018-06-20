---
swagger: "2.0"
x-collection-name: PagerDuty
x-complete: 0
info:
  title: PagerDuty Creating a service
  version: 1.0.0
  description: inventory services
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
    delete:
      summary: Delete a service
      description: Delete an existing service. Once the service is deleted, it will
        not be accessible from the web UI and new incidents won't be able to be created
        for this service.
      operationId: delete-an-existing-service-once-the-service-is-deleted-it-will-not-be-accessible-from-the-web-ui-and
      x-api-path-slug: servicesid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Services
    put:
      summary: Update a service
      description: Update an existing service.
      operationId: update-an-existing-service
      x-api-path-slug: servicesid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: service
        description: The service to be updated
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Services
  /inventory/services:
    "":
      summary: Creating a service
      description: inventory services
      operationId: creating-a-service
      x-api-path-slug: inventoryservices-
      parameters:
      - in: body
        name: auth
        description: Basic HTTP auth username and password
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: body
        description: HTTP Check - Content of the HTTP requestbody
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: checkLocations
        description: A JSON list of locations to check from e
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: checkMethod
        description: 'HTTP Check - The HTTP method used to issue the check: either
          GET, POST, PUT or DELETE'
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: checkType
        description: 'The type of check: either http or tcp'
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: checkUrl
        description: HTTP Check - The URL to issue the request to
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: data
        description: TCP Check - The content to send when opening the TCP socket
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: group
        description: The group the service belongs to
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: headers
        description: HTTP Check - headers to include e
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: host
        description: TCP Check - The hostname or IP address to issue the TCP check
          to
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: name
        description: The display name for the service
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: port
        description: TCP Check - The port number to issue the TCP check to
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: slowThreshold
        description: HTTP Check - Request time millisecond threshold after which service
          is deemed slow
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: tags
        description: A JSON list of tag IDs
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: timeout
        description: How many seconds to wait until timing out
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: token
        description: Your API token
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: token
        description: Your API token
        type: string
      - in: body
        name: validateCert
        description: HTTP Check - Whether to validate the SSL certificate or not
        schema:
          $ref: '#/definitions/holder'
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