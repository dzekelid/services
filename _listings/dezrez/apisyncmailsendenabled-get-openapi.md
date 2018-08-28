---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez check if the user has setup their credientials for smtp services
  version: 1.0.0
  description: Check if the user has setup their credientials for smtp services.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/sync/mailsendenabled:
    get:
      summary: check if the user has setup their credientials for smtp services
      description: Check if the user has setup their credientials for smtp services.
      operationId: Sync_MailSendEnabled
      x-api-path-slug: apisyncmailsendenabled-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Check
      - If
      - User
      - Has
      - Setup
      - Their
      - Credientialssmtp
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