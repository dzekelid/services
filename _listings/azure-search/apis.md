---
name: Azure Search
x-slug: azure-search
description: Azure Search is a fully-managed service for adding sophisticated search
  capabilities to web and mobile applications without the typical complexities of
  full-text search.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-search.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Services
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/apis.md
specificationVersion: "0.14"
apis:
- name: SearchManagementClient - Services Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-put
  description: Creates or updates a Search service in the given resource group. If
    the Search service already exists, all properties will be updated with the given
    values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-search.png
  humanURL: https://azure.microsoft.com/en-us/services/search/
  baseURL: ://management.azure.com//
  tags: Search, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-put-openapi.md
- name: SearchManagementClient - Services Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-get
  description: Gets the Search service with the given name in the given resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-search.png
  humanURL: https://azure.microsoft.com/en-us/services/search/
  baseURL: ://management.azure.com//
  tags: Search, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-get-openapi.md
- name: SearchManagementClient - Services Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-delete
  description: Deletes a Search service in the given resource group, along with its
    associated resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-search.png
  humanURL: https://azure.microsoft.com/en-us/services/search/
  baseURL: ://management.azure.com//
  tags: Search, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.scheduler.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.search.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/search/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/search/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/search/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/search/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---