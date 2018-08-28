---
swagger: "2.0"
x-collection-name: OnSched
x-complete: 0
info:
  title: OnSched Returns a list of services.
  description: "The results are returned in pages. Use the offset and limit parameters
    to control the page start and size. Default offset is 0, and limit is 20.\r\nUse
    the other query parameters to optionally filter the results list."
  termsOfService: None
  contact:
    name: OnSched.com
    url: https://onsched.com
    email: info@onsched.com
  version: 1.0.0
host: api.onsched.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /consumer/v1/resources/{id}/services:
    get:
      summary: Returns a list of resource services.
      description: "The results are returned in pages. Use the offset and limit parameters
        to control the page start and size. Default offset is 0, and limit is 20.\r\nUse
        the other query parameters to optionally filter the results list.\r\nResource
        services are used to explicitly define the services that can be booked for
        a resource. If no resource services are defined then by\r\ndefault all services
        can be booked for the resource."
      operationId: ConsumerV1ResourcesByIdServicesGet
      x-api-path-slug: consumerv1resourcesidservices-get
      parameters:
      - in: path
        name: id
        description: The id of the resource object
      - in: query
        name: limit
        description: Page limit, default 20
      - in: query
        name: offset
        description: Starting row of page, default 0
      responses:
        200:
          description: OK
      tags:
      - Resources
      - Services
  /consumer/v1/services:
    get:
      summary: Returns a list of services.
      description: "The results are returned in pages. Use the offset and limit parameters
        to control the page start and size. Default offset is 0, and limit is 20.\r\nUse
        the other query parameters to optionally filter the results list."
      operationId: ConsumerV1ServicesGet
      x-api-path-slug: consumerv1services-get
      parameters:
      - in: query
        name: defaultService
        description: Filter services by default service
      - in: query
        name: limit
        description: Page limit, default 20
      - in: query
        name: locationId
        description: The id of the business location
      - in: query
        name: offset
        description: Starting row of page, default 0
      - in: query
        name: serviceGroupId
        description: Filter services by group
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