---
name: Kubernetes
x-slug: kubernetes
description: Manage a cluster of Linux containers as a single system to accelerate
  Dev and simplify Ops. Kubernetes is an open source orchestration system for Docker
  containers. It handles scheduling onto nodes in a compute cluster and actively manages
  workloads to ensure that their state matches the users declared intentions. Using
  the concepts of labels and pods, it groups the containers which make up an application
  into logical units for easy management and discovery.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Services
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apis.md
specificationVersion: "0.14"
apis:
- name: Kubernetes - Get Namespaces Services
  x-api-slug: apiv1beta3namespacesnamespacesservices-get
  description: List objects of kind service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3namespacesnamespacesservices-get-openapi.md
- name: Kubernetes - Post Namespaces Services
  x-api-slug: apiv1beta3namespacesnamespacesservices-post
  description: Create a service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3namespacesnamespacesservices-post-openapi.md
- name: Kubernetes - Delete Namespaces Services Name
  x-api-slug: apiv1beta3namespacesnamespacesservicesname-delete
  description: Delete a service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3namespacesnamespacesservicesname-delete-openapi.md
- name: Kubernetes - Get Namespaces Services Name
  x-api-slug: apiv1beta3namespacesnamespacesservicesname-get
  description: Read the specified service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3namespacesnamespacesservicesname-get-openapi.md
- name: Kubernetes - Put Namespaces Services Name
  x-api-slug: apiv1beta3namespacesnamespacesservicesname-put
  description: Update the specified service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3namespacesnamespacesservicesname-put-openapi.md
- name: Kubernetes - Delete Proxy Namespaces Services Name
  x-api-slug: apiv1beta3proxynamespacesnamespacesservicesname-delete
  description: Proxy delete requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesname-delete-openapi.md
- name: Kubernetes - Get Proxy Namespaces Services Name
  x-api-slug: apiv1beta3proxynamespacesnamespacesservicesname-get
  description: Proxy get requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesname-get-openapi.md
- name: Kubernetes - Post Proxy Namespaces Services Name
  x-api-slug: apiv1beta3proxynamespacesnamespacesservicesname-post
  description: Proxy post requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesname-post-openapi.md
- name: Kubernetes - Put Proxy Namespaces Services Name
  x-api-slug: apiv1beta3proxynamespacesnamespacesservicesname-put
  description: Proxy put requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesname-put-openapi.md
- name: Kubernetes - Delete Proxy Namespaces Services Name Path *
  x-api-slug: apiv1beta3proxynamespacesnamespacesservicesnamepath-delete
  description: Proxy delete requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesnamepath-delete-openapi.md
- name: Kubernetes - Get Proxy Namespaces Services Name Path *
  x-api-slug: apiv1beta3proxynamespacesnamespacesservicesnamepath-get
  description: Proxy get requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesnamepath-get-openapi.md
- name: Kubernetes - Post Proxy Namespaces Services Name Path *
  x-api-slug: apiv1beta3proxynamespacesnamespacesservicesnamepath-post
  description: Proxy post requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesnamepath-post-openapi.md
- name: Kubernetes - Put Proxy Namespaces Services Name Path *
  x-api-slug: apiv1beta3proxynamespacesnamespacesservicesnamepath-put
  description: Proxy put requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesnamepath-put-openapi.md
- name: Kubernetes - Get Redirect Namespaces Services Name
  x-api-slug: apiv1beta3redirectnamespacesnamespacesservicesname-get
  description: Redirect get request to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3redirectnamespacesnamespacesservicesname-get-openapi.md
- name: Kubernetes - Get Services
  x-api-slug: apiv1beta3services-get
  description: List objects of kind service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3services-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Services
  x-api-slug: apiv1beta3watchnamespacesnamespacesservices-get
  description: Watch a list of service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespacesservices-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Services Name
  x-api-slug: apiv1beta3watchnamespacesnamespacesservicesname-get
  description: Watch a particular service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespacesservicesname-get-openapi.md
- name: Kubernetes - Get Watch Services
  x-api-slug: apiv1beta3watchservices-get
  description: Watch a list of service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3watchservices-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://knoema.api.gallery.streamdata.io
- type: x-api-stack
  url: http://kubernetes.stack.network
- type: x-blog
  url: http://blog.kubernetes.io/
- type: x-blog-rss
  url: http://blog.kubernetes.io/feeds/posts/default
- type: x-github
  url: https://github.com/kubernetes
- type: x-twitter
  url: https://twitter.com/kubernetesio
- type: x-website
  url: http://kubernetes.io/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---