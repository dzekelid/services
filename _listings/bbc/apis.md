---
name: BBC
x-slug: bbc
description: Breaking news, sport, TV, radio and a whole lot more. The BBC informs,
  educates and entertains - wherever you are, whatever your age.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
x-kinRank: "7"
x-alexaRank: "93"
tags: Services
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/bbc/apis.md
specificationVersion: "0.14"
apis:
- name: BBC Nitro - Information about the linear services used for broadcast transmissions
  x-api-slug: services-get
  description: The services feed exposes the linear broadcast "services" from PIPs.
    These are the actual services which broadcast programmes (eg bbc_one_oxford is
    the service for BBC One in Oxford).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api
  tags: Media, API Provider, Broadcasts, Profiles, Publish, General Data, Historical
    Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/bbc/services-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/services/master/_listings/bbc/services-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://barclays.api.gallery.streamdata.io
- type: x-api-stack
  url: http://bbc.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/bbc-news
- type: x-email
  url: dataprotection@bbc.com
- type: x-email
  url: bbcworldwidelearning@bbc.com
- type: x-twitter
  url: https://twitter.com/BBCNews
- type: x-website
  url: http://www.bbc.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---