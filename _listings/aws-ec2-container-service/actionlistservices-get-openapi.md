---
swagger: "2.0"
x-collection-name: AWS EC2 Container Service
x-complete: 0
info:
  title: Amazon EC2 Container Service API List Services
  version: 1.0.0
  description: Lists the services that are running in a specified cluster.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateService:
    get:
      summary: Create Service
      description: Runs and maintains a desired number of tasks from a specified task
        definition.
      operationId: createService
      x-api-path-slug: actioncreateservice-get
      parameters:
      - in: query
        name: clientToken
        description: Unique, case-sensitive identifier you provide to ensure the idempotency
          of the            request
        type: string
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          on which to run your service
        type: string
      - in: query
        name: deploymentConfiguration
        description: Optional deployment parameters that control how many tasks run
          during the            deployment and the ordering of stopping and starting
          tasks
        type: string
      - in: query
        name: desiredCount
        description: The number of instantiations of the specified task definition
          to place and keep            running on your cluster
        type: string
      - in: query
        name: loadBalancers
        description: A load balancer object representing the load balancer to use
          with your service
        type: string
      - in: query
        name: placementConstraints
        description: An array of placement constraint objects to use for tasks in
          your service
        type: string
      - in: query
        name: placementStrategy
        description: The placement strategy objects to use for tasks in your service
        type: string
      - in: query
        name: role
        description: The name or full Amazon Resource Name (ARN) of the IAM role that
          allows Amazon ECS to make calls to your            load balancer on your
          behalf
        type: string
      - in: query
        name: serviceName
        description: The name of your service
        type: string
      - in: query
        name: taskDefinition
        description: The family and revision (family:revision) or            full
          Amazon Resource Name (ARN) of the task definition to run in your service
        type: string
      responses:
        200:
          description: OK
      tags:
      - Services
  /?Action=DeleteService:
    get:
      summary: Delete Service
      description: Deletes a specified service within a cluster.
      operationId: deleteService
      x-api-path-slug: actiondeleteservice-get
      parameters:
      - in: query
        name: cluster
        description: The name of the cluster that hosts the service to delete
        type: string
      - in: query
        name: service
        description: The name of the service to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Services
  /?Action=DescribeServices:
    get:
      summary: Describe Services
      description: Describes the specified services running in your cluster.
      operationId: describeServices
      x-api-path-slug: actiondescribeservices-get
      parameters:
      - in: query
        name: cluster
        description: The name of the cluster that hosts the service to describe
        type: string
      - in: query
        name: services
        description: A list of services to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Services
  /?Action=ListServices:
    get:
      summary: List Services
      description: Lists the services that are running in a specified cluster.
      operationId: listServices
      x-api-path-slug: actionlistservices-get
      parameters:
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          that hosts the services to list
        type: string
      - in: query
        name: maxResults
        description: The maximum number of container instance results returned by                ListServices
          in paginated output
        type: string
      - in: query
        name: nextToken
        description: The nextToken value returned from a previous paginated                ListServices
          request where maxResults was used and the            results exceeded the
          value of that parameter
        type: string
      responses:
        200:
          description: OK
      tags:
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