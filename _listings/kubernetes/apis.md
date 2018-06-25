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
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apis.md
specificationVersion: "0.14"
apis:
- name: Kubernetes Get Namespaces Services
  x-api-slug: kubernetes
  description: List objects of kind service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/services
  tags: Namespaces,Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3namespacesnamespacesservices-get-openapi.md
- name: Kubernetes Post Namespaces Services
  x-api-slug: kubernetes
  description: Create a service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/services
  tags: Namespaces,Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3namespacesnamespacesservices-post-openapi.md
- name: Kubernetes Delete Namespaces Services Name
  x-api-slug: kubernetes
  description: Delete a service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/services/{name}
  tags: Namespaces,Services,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3namespacesnamespacesservicesname-delete-openapi.md
- name: Kubernetes Get Namespaces Services Name
  x-api-slug: kubernetes
  description: Read the specified service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/services/{name}
  tags: Namespaces,Services,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3namespacesnamespacesservicesname-get-openapi.md
- name: Kubernetes Put Namespaces Services Name
  x-api-slug: kubernetes
  description: Update the specified service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/services/{name}
  tags: Namespaces,Services,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3namespacesnamespacesservicesname-put-openapi.md
- name: Kubernetes Delete Proxy Namespaces Services Name
  x-api-slug: kubernetes
  description: Proxy delete requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/proxy/namespaces/{namespaces}/services/{name}
  tags: Proxy,Namespaces,Services,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesname-delete-openapi.md
- name: Kubernetes Get Proxy Namespaces Services Name
  x-api-slug: kubernetes
  description: Proxy get requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/proxy/namespaces/{namespaces}/services/{name}
  tags: Proxy,Namespaces,Services,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesname-get-openapi.md
- name: Kubernetes Post Proxy Namespaces Services Name
  x-api-slug: kubernetes
  description: Proxy post requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/proxy/namespaces/{namespaces}/services/{name}
  tags: Proxy,Namespaces,Services,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesname-post-openapi.md
- name: Kubernetes Put Proxy Namespaces Services Name
  x-api-slug: kubernetes
  description: Proxy put requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/proxy/namespaces/{namespaces}/services/{name}
  tags: Proxy,Namespaces,Services,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesname-put-openapi.md
- name: Kubernetes Delete Proxy Namespaces Services Name Path *
  x-api-slug: kubernetes
  description: Proxy delete requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/proxy/namespaces/{namespaces}/services/{name}/{path:*}
  tags: Proxy,Namespaces,Services,Name,Path,*
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesnamepath-delete-openapi.md
- name: Kubernetes Get Proxy Namespaces Services Name Path *
  x-api-slug: kubernetes
  description: Proxy get requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/proxy/namespaces/{namespaces}/services/{name}/{path:*}
  tags: Proxy,Namespaces,Services,Name,Path,*
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesnamepath-get-openapi.md
- name: Kubernetes Post Proxy Namespaces Services Name Path *
  x-api-slug: kubernetes
  description: Proxy post requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/proxy/namespaces/{namespaces}/services/{name}/{path:*}
  tags: Proxy,Namespaces,Services,Name,Path,*
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesnamepath-post-openapi.md
- name: Kubernetes Put Proxy Namespaces Services Name Path *
  x-api-slug: kubernetes
  description: Proxy put requests to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/proxy/namespaces/{namespaces}/services/{name}/{path:*}
  tags: Proxy,Namespaces,Services,Name,Path,*
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3proxynamespacesnamespacesservicesnamepath-put-openapi.md
- name: Kubernetes Get Redirect Namespaces Services Name
  x-api-slug: kubernetes
  description: Redirect get request to service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/redirect/namespaces/{namespaces}/services/{name}
  tags: Redirect,Namespaces,Services,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3redirectnamespacesnamespacesservicesname-get-openapi.md
- name: Kubernetes Get Services
  x-api-slug: kubernetes
  description: List objects of kind service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/services
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3services-get-openapi.md
- name: Kubernetes Get Watch Namespaces Services
  x-api-slug: kubernetes
  description: Watch a list of service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/watch/namespaces/{namespaces}/services
  tags: Watch,Namespaces,Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespacesservices-get-openapi.md
- name: Kubernetes Get Watch Namespaces Services Name
  x-api-slug: kubernetes
  description: Watch a particular service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/watch/namespaces/{namespaces}/services/{name}
  tags: Watch,Namespaces,Services,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespacesservicesname-get-openapi.md
- name: Kubernetes Get Watch Services
  x-api-slug: kubernetes
  description: Watch a list of service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/watch/services
  tags: Watch,Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/apiv1beta3watchservices-get-openapi.md
- name: Kubernetes
  x-api-slug: kubernetes
  description: Manage a cluster of Linux containers as a single system to accelerate
    Dev and simplify Ops. Kubernetes is an open source orchestration system for Docker
    containers. It handles scheduling onto nodes in a compute cluster and actively
    manages workloads to ensure that their state matches the users declared intentions.
    Using the concepts of labels and pods, it groups the containers which make up
    an application into logical units for easy management and discovery.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/kubernetes/openapi.md
x-common:
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