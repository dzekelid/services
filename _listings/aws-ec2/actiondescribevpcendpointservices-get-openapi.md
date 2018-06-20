---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Describe Vpc Endpoint Services
  version: 1.0.0
  description: Describes all supported AWS services that can be specified when creating
    a VPC endpoint.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeVpcEndpointServices:
    get:
      summary: Describe Vpc Endpoint Services
      description: Describes all supported AWS services that can be specified when
        creating a VPC endpoint.
      operationId: describevpcendpointservices
      x-api-path-slug: actiondescribevpcendpointservices-get
      parameters:
      - in: query
        name: AddRouteTableId.N
        description: One or more route tables IDs to associate with the endpoint
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: PolicyDocument
        description: A policy document to attach to the endpoint
        type: string
      - in: query
        name: RemoveRouteTableId.N
        description: One or more route table IDs to disassociate from the endpoint
        type: string
      - in: query
        name: ResetPolicy
        description: Specify true to reset the policy document to the default policy
        type: string
      - in: query
        name: VpcEndpointId
        description: The ID of the endpoint
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoint Services
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