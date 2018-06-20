---
name: PagerDuty
x-slug: pagerduty
description: See how PagerDuty Digital Operations Management Platform integrates machine
  data & human intelligence to improve visibility & agility across organizations.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
x-kinRank: "8"
x-alexaRank: "19574"
tags: Services
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/pagerduty/apis.md
specificationVersion: "0.14"
apis:
- name: PagerDuty List services
  x-api-slug: pagerduty
  description: List existing services.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/pagerduty/services-get-openapi.md
- name: PagerDuty Create a service
  x-api-slug: pagerduty
  description: Create a new service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/pagerduty/services-post-openapi.md
- name: PagerDuty Get a service
  x-api-slug: pagerduty
  description: Get details about an existing service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services/{id}
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/pagerduty/servicesid-get-openapi.md
- name: PagerDuty Delete a service
  x-api-slug: pagerduty
  description: Delete an existing service. Once the service is deleted, it will not
    be accessible from the web UI and new incidents won't be able to be created for
    this service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services/{id}
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/pagerduty/servicesid-delete-openapi.md
- name: PagerDuty Update a service
  x-api-slug: pagerduty
  description: Update an existing service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services/{id}
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/pagerduty/servicesid-put-openapi.md
- name: PagerDuty Creating a service
  x-api-slug: pagerduty
  description: inventory services
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///inventory/services
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/pagerduty/inventoryservices--openapi.md
- name: PagerDuty Updating a service
  x-api-slug: pagerduty
  description: inventory services service
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///inventory/services/serviceId
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/pagerduty/inventoryservicesserviceid--openapi.md
- name: PagerDuty Listing service groups
  x-api-slug: pagerduty
  description: inventory services groups token token
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///inventory/services/groups/?token=token
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/pagerduty/inventoryservicesgroupstokentoken--openapi.md
- name: PagerDuty
  x-api-slug: pagerduty
  description: See how PagerDuty Digital Operations Management Platform integrates
    machine data & human intelligence to improve visibility & agility across organizations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https:///
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/pagerduty/openapi.md
x-common:
- type: x-base
  url: https://acme.pagerduty.com/api/
- type: x-blog
  url: http://blog.pagerduty.com/
- type: x-blog-rss
  url: http://blog.pagerduty.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/pagerduty
- type: x-crunchbase
  url: https://crunchbase.com/organization/pagerduty
- type: x-developer
  url: http://developer.pagerduty.com/
- type: x-email
  url: info@pagerduty.com
- type: x-email
  url: sales@pagerduty.com
- type: x-email
  url: support@pagerduty.com
- type: x-email
  url: legal@pagerduty.com
- type: x-github
  url: https://github.com/PagerDuty
- type: x-openapi-spec--authoritative
  url: https://api-reference.pagerduty.com/output.json
- type: x-pricing
  url: https://www.pagerduty.com/pricing/
- type: x-twitter
  url: https://twitter.com/pagerduty
- type: x-website
  url: http://www.pagerduty.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---