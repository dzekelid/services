swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
  /api/sync/imapserversetup:
    get:
      summary: check if the user has setup their credientials for smtp services
      description: Check if the user has setup their credientials for smtp services.
      operationId: Sync_ImapServerSetup
      x-api-path-slug: apisyncimapserversetup-get
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