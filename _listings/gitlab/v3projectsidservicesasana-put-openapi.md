---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 0
info:
  title: GitLab Put Projects Services Asana
  version: 1.0.0
  description: Set asana service for project
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/projects/{id}/services/asana:
    put:
      summary: Put Projects Services Asana
      description: Set asana service for project
      operationId: putV3ProjectsIdServicesAsana
      x-api-path-slug: v3projectsidservicesasana-put
      parameters:
      - in: formData
        name: api_key
        description: User API token
      - in: path
        name: id
      - in: formData
        name: push_events
        description: Event will be triggered by a push to the repository
      - in: formData
        name: restrict_to_branch
        description: Comma-separated list of branches which will be automatically
          inspected
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Services
      - Asana
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