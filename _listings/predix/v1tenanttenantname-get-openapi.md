---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Tenant Management Retrieve a tenant and its list of services
  description: Retrieve a tenant and its list of services.
  version: 1.0.0
host: predix-tms.run.aws-usw02-pr.ice.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/tenant/{tenantName}:
    get:
      summary: Retrieve a tenant and its list of services
      description: Retrieve a tenant and its list of services.
      operationId: getTenantUsingGET
      x-api-path-slug: v1tenanttenantname-get
      parameters:
      - in: header
        name: Predix-Zone-Id
      - in: path
        name: tenantName
        description: tenantName
      responses:
        200:
          description: Successful response
      tags:
      - Retrieve
      - Tenant
      - Its
      - List
      - Of
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