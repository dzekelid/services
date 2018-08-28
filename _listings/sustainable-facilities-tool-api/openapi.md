swagger: "2.0"
x-collection-name: Sustainable Facilities Tool API
x-complete: 1
info:
  title: Sustainable Facilities Tool API
  description: our-core-api-allows-developers-to-interact-with-the-sustainable-facilities-tool-programmatically--its-designed-for-public-use-and-to-be-easily-integrated-into-other-applications-
  termsOfService: https://sftool.gov/developer/terms-of-use
  version: 1.0.0
host: api.data.gov
basePath: /sftool/v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /services:
    get:
      summary: Services
      description: Returns all services
      operationId: getServices
      x-api-path-slug: services-get
      responses:
        200:
          description: OK
      tags:
      - Services
  /services/{parameter}:
    get:
      summary: Services
      description: Returns a service by parameter.
      operationId: getService
      x-api-path-slug: servicesparameter-get
      responses:
        200:
          description: OK
      tags:
      - Services