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
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Search API Services Create Or Update
  x-api-slug: azure-search-api
  description: Creates or updates a Search service in the given resource group. If
    the Search service already exists, all properties will be updated with the given
    values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-search.png
  humanURL: https://azure.microsoft.com/en-us/services/search/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Search/searchServices/{searchServiceName}
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-put-openapi.md
- name: Azure Search API Services Get
  x-api-slug: azure-search-api
  description: Gets the Search service with the given name in the given resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-search.png
  humanURL: https://azure.microsoft.com/en-us/services/search/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Search/searchServices/{searchServiceName}
  tags: Services
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-get-openapi.md
- name: Azure Search API Services Delete
  x-api-slug: azure-search-api
  description: Deletes a Search service in the given resource group, along with its
    associated resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-search.png
  humanURL: https://azure.microsoft.com/en-us/services/search/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Search/searchServices/{searchServiceName}
  tags: Services
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservicessearchservicename-delete-openapi.md
- name: Azure Search API Services List By Resource Group
  x-api-slug: azure-search-api
  description: Gets a list of all Search services in the given resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-search.png
  humanURL: https://azure.microsoft.com/en-us/services/search/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Search/searchServices
  tags: Services Resource Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-searchsearchservices-get-openapi.md
- name: Azure Search API Services Check Name Availability
  x-api-slug: azure-search-api
  description: Checks whether or not the given Search service name is available for
    use. Search service names must be globally unique since they are part of the service
    URI (https://<name>.search.windows.net).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-search.png
  humanURL: https://azure.microsoft.com/en-us/services/search/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Search/checkNameAvailability
  tags: Services Name Availability
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/subscriptionssubscriptionidprovidersmicrosoft-searchchecknameavailability-post-openapi.md
- name: Azure Search API
  x-api-slug: azure-search-api
  description: Azure Search is a fully-managed service for adding sophisticated search
    capabilities to web and mobile applications without the typical complexities of
    full-text search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-search.png
  humanURL: https://azure.microsoft.com/en-us/services/search/
  baseURL: ://management.azure.com//
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/azure-search/openapi.md
x-common:
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