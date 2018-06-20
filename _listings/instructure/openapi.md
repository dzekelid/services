---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Utility APIs
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /services/kaltura:
    get:
      summary: Get Kaltura config
      description: Get kaltura config.
      operationId: get-kaltura-config
      x-api-path-slug: serviceskaltura-get
      responses:
        200:
          description: OK
      tags:
      - Services
      - Kaltura
  /services/kaltura_session:
    post:
      summary: Start Kaltura session
      description: Start kaltura session.
      operationId: start-kaltura-session
      x-api-path-slug: serviceskaltura-session-post
      responses:
        200:
          description: OK
      tags:
      - Services
      - Kaltura
      - Session
---