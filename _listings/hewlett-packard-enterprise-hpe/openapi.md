swagger: "2.0"
x-collection-name: Hewlett Packard Enterprise (HPE)
x-complete: 1
info:
  title: HPE OneSphere API
  description: hpe-onesphere-hybrid-cloud-management-rest-api-for-calls-requiring-authentication-use-restsession-to-get-a-token-
  termsOfService: http://www.hpe.com/onesphere
  contact:
    name: HPE OneSphere API team
    url: http://www.hpe.com/onesphere
  version: 1.0.0
host: deic02-hpe.hpeonesphere.com
basePath: /rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /services:
    get:
      summary: Get Services
      description: Returns services. It requires any project role or non-'consumer'
        global role.
      operationId: FindServices
      x-api-path-slug: services-get
      parameters:
      - in: query
        name: query
        description: Filters the services returned
      - in: query
        name: userQuery
        description: Filters the services returned
      - in: query
        name: view
        description: 'Return related resources:  * `full` - Include all the details
          of the services'
      responses:
        200:
          description: OK
      tags:
      - Services
  /services/{id}:
    get:
      summary: Get Services
      description: Returns a service based on its id. It requires any project role
        or non-'consumer' global role.
      operationId: GetServiceById
      x-api-path-slug: servicesid-get
      parameters:
      - in: path
        name: id
        description: ID of service to fetch
      - in: query
        name: view
        description: 'Return related resources:  * `full` - Include all the details
          of the services  * `deployment` - Return the zones to which the service
          can be deployed'
      responses:
        200:
          description: OK
      tags:
      - Services