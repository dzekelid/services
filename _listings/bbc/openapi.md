swagger: "2.0"
x-collection-name: BBC
x-complete: 1
info:
  title: BBC Nitro
  description: bbc-nitro-is-the-bbcs-application-programming-interface-api-for-bbc-programmes-metadata-
  termsOfService: http://www.bbc.co.uk/terms/
  contact:
    name: Open Nitro Project
    url: http://developer.bbc.co.uk/
    email: nitro@bbc.co.uk
  version: 1.0.0
host: programmes.api.bbc.com
basePath: /nitro/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /services:
    get:
      summary: Information about the linear services used for broadcast transmissions
      description: The services feed exposes the linear broadcast "services" from
        PIPs. These are the actual services which broadcast programmes (eg bbc_one_oxford
        is the service for BBC One in Oxford).
      operationId: listServices
      x-api-path-slug: services-get
      parameters:
      - in: query
        name: end_from
        description: Return services that end on or later than the specified datetime
      - in: query
        name: end_to
        description: filter for subset of broadcasts that end on or earlier than the
          specified datetime
      - in: query
        name: mid
        description: filter for services by masterbrand MID
      - in: query
        name: page
        description: which page of results to return
      - in: query
        name: page_size
        description: number of results in each page
      - in: query
        name: partner_id
        description: filter for services by partner ID
      - in: query
        name: partner_pid
        description: filter for services by partner PID
      - in: query
        name: q
        description: filter for subset of services matching supplied keyword/phrase
          (boolean operators permitted)
      - in: query
        name: service_type
        description: filter for specified type of linear services
      - in: query
        name: sid
        description: filter for specified linear service
      - in: query
        name: start_from
        description: Return services that start on or later than the specified datetime
      - in: query
        name: start_to
        description: Return services that start earlier than the specified datetime
      responses:
        200:
          description: OK
      tags:
      - Services