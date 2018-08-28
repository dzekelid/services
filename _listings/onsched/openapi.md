swagger: "2.0"
x-collection-name: OnSched
x-complete: 1
info:
  title: OnSched API
  description: build-secure-and-scalable-custom-apps-for-online-booking--our-flexible-api-provides-many-options-for-availability-and-booking--take-the-api-for-a-test-drive--just-click-on-the-authorize-button-above-and-authenticate---you-can-access-our-demo-company-profile-if-you-are-not-a-customer-or-your-own-profile-by-using-your-assigned-clientid-and-secret---------------------
  termsOfService: None
  contact:
    name: OnSched.com
    url: https://onsched.com
    email: info@onsched.com
  version: 1.0.0
host: api.onsched.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /consumer/v1/resources/{id}/services:
    get:
      summary: Returns a list of resource services.
      description: "The results are returned in pages. Use the offset and limit parameters
        to control the page start and size. Default offset is 0, and limit is 20.\r\nUse
        the other query parameters to optionally filter the results list.\r\nResource
        services are used to explicitly define the services that can be booked for
        a resource. If no resource services are defined then by\r\ndefault all services
        can be booked for the resource."
      operationId: ConsumerV1ResourcesByIdServicesGet
      x-api-path-slug: consumerv1resourcesidservices-get
      parameters:
      - in: path
        name: id
        description: The id of the resource object
      - in: query
        name: limit
        description: Page limit, default 20
      - in: query
        name: offset
        description: Starting row of page, default 0
      responses:
        200:
          description: OK
      tags:
      - Resources
      - Services
  /consumer/v1/services:
    get:
      summary: Returns a list of services.
      description: "The results are returned in pages. Use the offset and limit parameters
        to control the page start and size. Default offset is 0, and limit is 20.\r\nUse
        the other query parameters to optionally filter the results list."
      operationId: ConsumerV1ServicesGet
      x-api-path-slug: consumerv1services-get
      parameters:
      - in: query
        name: defaultService
        description: Filter services by default service
      - in: query
        name: limit
        description: Page limit, default 20
      - in: query
        name: locationId
        description: The id of the business location
      - in: query
        name: offset
        description: Starting row of page, default 0
      - in: query
        name: serviceGroupId
        description: Filter services by group
      responses:
        200:
          description: OK
      tags:
      - Services
  /consumer/v1/services/{id}:
    get:
      summary: Returns a service object.
      description: "The result returned is a single service object. An id is required
        to find the service. Find service id's using either the GET consumer/v1/service
        end point,\r\nor the GET consumer/v1/appointments end point."
      operationId: ConsumerV1ServicesByIdGet
      x-api-path-slug: consumerv1servicesid-get
      parameters:
      - in: path
        name: id
        description: The id of the service object
      responses:
        200:
          description: OK
      tags:
      - Services
  /consumer/v1/services/{id}/resources:
    get:
      summary: Returns a list of resources.
      description: "The results are returned in pages. Use the offset and limit parameters
        to control the page start and size. Default offset is 0, and limit is 20.\r\nUse
        the other query parameters to optionally filter the results list."
      operationId: ConsumerV1ServicesByIdResourcesGet
      x-api-path-slug: consumerv1servicesidresources-get
      parameters:
      - in: path
        name: id
        description: The id of the service object
      - in: query
        name: limit
        description: Page limit, default 20
      - in: query
        name: offset
        description: Starting row of page, default 0
      responses:
        200:
          description: OK
      tags:
      - Services
      - Resources