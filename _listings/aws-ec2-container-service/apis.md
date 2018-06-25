---
name: AWS EC2 Container Service
x-slug: aws-ec2-container-service
description: Amazon EC2 Container Service (ECS) is a highly scalable, high performance
  container management service that supports Docker containers and allows you to easily
  run applications on a managed cluster of Amazon EC2 instances. Amazon ECS eliminates
  the need for you to install, operate, and scale your own cluster management infrastructure.
  With simple API calls, you can launch and stop Docker-enabled applications, query
  the complete state of your cluster, and access many familiar features like security
  groups, Elastic Load Balancing, EBS volumes, and IAM roles. You can use Amazon ECS
  to schedule the placement of containers across your cluster based on your resource
  needs and availability requirements. You can also integrate your own scheduler or
  third-party schedulers to meet business or application specific requirements.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Services
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/aws-ec2-container-service/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon EC2 Container Service API Create Service
  x-api-slug: amazon-ec2-container-service-api
  description: Runs and maintains a desired number of tasks from a specified task
    definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=CreateService
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/aws-ec2-container-service/actioncreateservice-get-openapi.md
- name: Amazon EC2 Container Service API Delete Service
  x-api-slug: amazon-ec2-container-service-api
  description: Deletes a specified service within a cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DeleteService
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/aws-ec2-container-service/actiondeleteservice-get-openapi.md
- name: Amazon EC2 Container Service API Describe Services
  x-api-slug: amazon-ec2-container-service-api
  description: Describes the specified services running in your cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DescribeServices
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/aws-ec2-container-service/actiondescribeservices-get-openapi.md
- name: Amazon EC2 Container Service API List Services
  x-api-slug: amazon-ec2-container-service-api
  description: Lists the services that are running in a specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=ListServices
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/aws-ec2-container-service/actionlistservices-get-openapi.md
- name: Amazon EC2 Container Service API Update Service
  x-api-slug: amazon-ec2-container-service-api
  description: |-
    Modifies the desired count, deployment configuration, or task definition used in a
                service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=UpdateService
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/aws-ec2-container-service/actionupdateservice-get-openapi.md
- name: Amazon EC2 Container Service API
  x-api-slug: amazon-ec2-container-service-api
  description: Amazon EC2 Container Service (ECS) is a highly scalable, high performance
    container management service that supports Docker containers and allows you to
    easily run applications on a managed cluster of Amazon EC2 instances. Amazon ECS
    eliminates the need for you to install, operate, and scale your own cluster management
    infrastructure. With simple API calls, you can launch and stop Docker-enabled
    applications, query the complete state of your cluster, and access many familiar
    features like security groups, Elastic Load Balancing, EBS volumes, and IAM roles.
    You can use Amazon ECS to schedule the placement of containers across your cluster
    based on your resource needs and availability requirements. You can also integrate
    your own scheduler or third-party schedulers to meet business or application specific
    requirements.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/aws-ec2-container-service/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonECS/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/ecs/faqs/
- type: x-getting-started
  url: https://portal.aws.amazon.com/gp/aws/developer/registration/index.html
- type: x-pricing
  url: https://aws.amazon.com/ecs/pricing/
- type: x-website
  url: https://aws.amazon.com/ecs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---