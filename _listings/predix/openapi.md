swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
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