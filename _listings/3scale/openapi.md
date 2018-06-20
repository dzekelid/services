---
swagger: "2.0"
x-collection-name: 3scale
x-complete: 1
info:
  title: 3Scale Account Management API
  description: the-api-for-managing-3scale-accounts-
  termsOfService: http://www.3scale.net/terms-and-conditions/
  contact:
    name: 3Scale
    url: https://support.3scale.net/
  version: "1"
host: su1.3scale.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/api/applications.xml:
    get:
      summary: Application List (all services)
      description: Application list (all services).
      operationId: application
      x-api-path-slug: adminapiapplications-xml-get
      parameters:
      - in: query
        name: active_since
        description: filter date
      - in: query
        name: inactive_since
        description: filter date
      - in: query
        name: page
        description: Page in the paginated list
      - in: query
        name: per_page
        description: Number of results per page
      - in: query
        name: provider_key
        description: Your api key with 3scale (also known as provider key)
      - in: query
        name: service_id
        description: filter by service
      responses:
        200:
          description: OK
      tags:
      - Application
      - List
      - (all
      - Services)
  /admin/api/application_plans.xml:
    get:
      summary: Application Plan List (all services)
      description: Application plan list (all services).
      operationId: application_plan
      x-api-path-slug: adminapiapplication-plans-xml-get
      parameters:
      - in: query
        name: provider_key
        description: Your api key with 3scale (also known as provider key)
      responses:
        200:
          description: OK
      tags:
      - Application
      - Plan
      - List
      - (all
      - Services)
  /admin/api/end_user_plans.xml:
    get:
      summary: End User Plan List (all services)
      description: End user plan list (all services).
      operationId: end_user_plan
      x-api-path-slug: adminapiend-user-plans-xml-get
      parameters:
      - in: query
        name: provider_key
        description: Your api key with 3scale (also known as provider key)
      responses:
        200:
          description: OK
      tags:
      - End
      - User
      - Plan
      - List
      - (all
      - Services)
  /admin/api/service_plans.xml:
    get:
      summary: Service Plan List (all services)
      description: Service plan list (all services).
      operationId: service_plan
      x-api-path-slug: adminapiservice-plans-xml-get
      parameters:
      - in: query
        name: provider_key
        description: Your api key with 3scale (also known as provider key)
      responses:
        200:
          description: OK
      tags:
      - Service
      - Plan
      - List
      - (all
      - Services)
---